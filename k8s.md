# Lab16 Kubernetes 
## Kubernetes Installation 
系統: ubuntu 20.04

To install minikube on x86-64 Linux using Debian package:
```bash=
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube_latest_amd64.deb
sudo dpkg -i minikube_latest_amd64.deb
```
![](https://i.imgur.com/EgEbtp7.png)

## Workload Deployment
### Use Deployment
This is `web-deployment.yaml`. 
```yaml=
apiVersion: apps/v1
kind: Deployment
metadata:
  name: web-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: web-api
  template:
    metadata:
      labels:
        app: web-api
    spec:
      containers:
      - name: simple-web-api
        image: msiciots/lab14_web:latest
        command: ["python"]
        args: ["server.py"]
        ports:
        - containerPort: 8080  
```
```bash=
kubectl create -f ./web-deployment.yaml
```
![](https://i.imgur.com/S1TkfO6.png)
![](https://i.imgur.com/0iXrIKZ.png)

### Use DaemonSet
This is `web-daemonset.yaml`. 
```yaml=
apiVersion: apps/v1
kind: DaemonSet
metadata:
  name: web-daemonset
spec:
  selector:
    matchLabels:
      app: web-api
  template:
    metadata:
      labels:
        app: web-api
    spec:
      tolerations:
      # this toleration is to have the daemonset runnable on master nodes
      # remove it if your masters can't run pods
      - key: node-role.kubernetes.io/master
        operator: Exists
        effect: NoSchedule
      containers:
      - name: simple-web-api
        image: msiciots/lab14_web:latest
        command: ["python"]
        args: ["server.py"]
        ports:
        - containerPort: 8080
```
```bash=
kubectl create -f web-daemonset.yaml
```
![](https://i.imgur.com/csOhuiy.png)
![](https://i.imgur.com/aM8Y2sM.png)
![](https://i.imgur.com/9IrH8Bb.png)
![](https://i.imgur.com/xhQ2hwz.png)


## Service Deployment
This is `web-deployment-service.yaml`.
```yaml=
apiVersion: v1
kind: Service
metadata:
  name: webapi-service
spec:
  type: NodePort
  ports:
  - port: 8080
    protocol: TCP
    targetPort: 8080
  selector:
    app: web-api 
```
![](https://i.imgur.com/jN2yXsw.png)

## Shell script
List all running pods
```bash=
kubectl get pods --field-selector=status.phase=Running
```
Delete all running pods
```bash=
kubectl get pods --field-selector=status.phase=Running | awk 'NR == 1 {next} {print $1}' | xargs kubectl delete pod
```
## CronJob
This is `cronjob.yaml`.
```yaml=
apiVersion: batch/v1beta1
kind: CronJob
metadata:
  name: hello-cronjob 
spec:
  schedule: "*/1 * * * *"
  jobTemplate:
    spec:
      template:
        spec:
          containers:
          - name: hello-cronjob 
            image: busybox
            imagePullPolicy: IfNotPresent
            command:
            - /bin/sh
            - -c
            - echo "Hi, current time is $(date)"
          restartPolicy: OnFailure 
```

![](https://i.imgur.com/VFB8rBV.png)
![](https://i.imgur.com/PfzjR2r.png)
![](https://i.imgur.com/hIkoTt4.png)
![](https://i.imgur.com/OZAB06p.png)