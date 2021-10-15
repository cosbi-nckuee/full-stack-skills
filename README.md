# full-stack-skills
###### tags: `cosbi`
## 主流技術
- [Stack Overflow - 2021 Developer Survey](https://insights.stackoverflow.com/survey/2021)
- [前端工程師 React Frontend Engineer(JoSeal)](https://www.cakeresume.com/companies/pagamo-org/jobs/frontend-developer-joseal)

- [後端工程師 NodeJs Backend Developer(JoSeal)](https://www.cakeresume.com/companies/pagamo-org/jobs/backend-developer-joseal-831fdc)
## FrontEnd
- [Vue vs React in 2021: Which Framework to Choose and When](https://www.monterail.com/blog/vue-vs-react-2021)
- [Angular vs React vs Vue:哪一个是2021年的最佳选择](http://jiagoushi.pro/angular-vs-react-vs-vue-which-best-choice-2021)
### [Vue.js](https://vuejs.org/)
Vue (音同View) 是一套以視圖層為基礎發展的 JavaScript 漸進式框架。
與其他前端框架/函式庫不同的是，Vue.js 的目標是透過簡單的 API 提供開發者實作資料綁定與操作網頁上的元件，同時也因為 Vue.js 的核心把焦點關注在狀態與畫面的同步層級上，遂能夠輕易地與其他 JavaScript 函式庫、前端開發工具鍊等整合使用，成為一套完整的前端開發方案。
- [JavaScript DOM (背景知識)](https://www.fooish.com/javascript/dom/)
- [重新認識 Vue.js (中文書)](https://book.vue.tw/)
### [React.js](https://zh-hant.reactjs.org/)
React 是一個陳述式、高效且具有彈性的 JavaScript 函式庫，用以建立使用者介面。它讓你使用小巧而獨立的「component」，來建立複雜的 UI。
- [65 Game Examples with ReactJS - React Rocks](https://react.rocks/tag/Game)

### [React Native](https://reactnative.dev/)
- [Github](https://github.com/facebook/react-native)
- [React Native 簡介：以 JavaScript 建構 iOS App](https://www.appcoda.com.tw/react-native-introduction/)
- [Video Demo](https://www.youtube.com/watch?v=x6baGsEQhcU&ab_channel=Vivek)
### SSR
- [[Day 14] Server-Side-Rendering - (1)](https://ithelp.ithome.com.tw/articles/10244948)
- [[Day 15] Server-Side-Rendering - (2) feat. Next.js](https://ithelp.ithome.com.tw/articles/10245758)
- [Next.js ](https://nextjs.org/)
- [Vue.js Server-Side Rendering Guide](https://ssr.vuejs.org/#what-is-server-side-rendering-ssr)

### [Webpack](https://webpack.js.org/) 
- [從模組化帶你認識 Webpack](https://5xruby.tw/posts/webpack)
### [Babel](https://babeljs.io/)
Babel 是 JavaScript 轉譯器，可將 ES6+ 程式碼轉為等效的 ES5 程式碼，我們在撰寫程式時就可以使用新的語法特性來改善程式碼的品質，而不用刻意守在舊有的手法。在實際執行 JavaScript 程式時，則會以普遍受到支援的 ES5 來執行，不用考慮 ES6 實作不夠完整的議題。
- [Babel 簡介](https://f2e.kalan.dev/frontend-engineering/9.html)
### [ESLint](https://eslint.org/)
ESLint 是眾多 JavaScript Linter 的其中一個，其優秀的支援性以及可自定義規則等功能，使他漸漸成為市場主流，其他包含 JSLint、JSHint、JSCS 等等，這些也都屬於 JS Linter，通常 Linter 大都具備以下功能：
1. 編碼規範：使用單引號還是雙引號、需不需要加分號、縮排使用 space 或 tab
2. 變數宣告：禁止未宣告變數直接取用，以塊級作用域而非函式作用域下宣告變數
3. 無效程序：已宣告卻未使用的變數、函式，建議刪除
4. 代碼測試：alert、console 行為，建議刪除

- [[JS] 使用 ESLint 提高程式碼品質](https://larrylu.blog/improve-code-quality-using-eslint-742cf1f384f1)
- [Day01【ES6 小筆記】ESLint 工具簡介&安裝教學-來個乾淨的程式碼](https://ithelp.ithome.com.tw/articles/10213146)
- [ESLint Demo](https://eslint.bootcss.com/demo/)
## BackEnd
### [Node.js](https://nodejs.org/)
Node.js 是什麼呢？根據官網的說法：
> Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

「runtime」 指的是執行環境，就如同網頁上的 JavaScript 是在瀏覽器的 JavaScript 引擎上執行，Node.js 就是一個能執行 JavaScript 的環境，而 V8 則是主流瀏覽器 - Google Chrome 的 JavaScript 引擎，負責解析、執行 JavaScript。
Node.js 以 V8 為核心，加上一系列 C/C++ 的套件，成功的讓 Server 端也可以執行 JavaScript。
- [Node.js v16.10.0 documentation](https://nodejs.org/api/synopsis.html)
- [Express.js](https://expressjs.com/zh-tw/)
- [[筆記] Django vs. Express](https://medium.com/hobo-engineer/ricky%E7%AD%86%E8%A8%98-django-vs-express-2e30e61aa23d)
- [Express vs. Django: 10 Indicators to Choose the True Backend King](https://www.simform.com/blog/express-vs-django/)
- [15 Companies That Use Node.js in 2021 Successfully](https://trio.dev/blog/companies-use-node-js)
- [LINE Developers - (Tutorial) Make a sample reply bot using Node.js](https://developers.line.biz/en/docs/messaging-api/nodejs-sample/#start-developing)
    - [Github - LINE Messaging API SDK for nodejs](https://github.com/line/line-bot-sdk-nodejs)
## [electron](https://www.electronjs.org/)
Electron 是一個將 JavaScript、HTML 與 CSS 等網頁技術轉換為桌面應用程式的框架，轉換後可於 Mac、Windows 以及 Linux 上運行。
- [electron-quick-start](https://github.com/electron/electron-quick-start)
- [Electron - 用網頁技術做一個桌面應用程式吧！](https://ithelp.ithome.com.tw/articles/10254357)

很多知名的桌面應用程式都是使用 Electron 開發的例如：
- [Github Desktop](https://desktop.github.com/)
- [Discord](https://discordapp.com/)
- [WordPress.com](https://wordpress.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Slack](https://slack.com/)
- [Atom](https://atom.io/)
## Cloud Platform
- [Compare AWS and Azure services to Google Cloud](https://cloud.google.com/free/docs/aws-azure-gcp-service-comparison)
- [雲端平台流量費用大比拼：Google (GCP) vs. Amazon vs. Microsoft](https://www.mile.cloud/zh/resources/blog/185/%E9%9B%B2%E7%AB%AF%E5%B9%B3%E5%8F%B0%E5%A4%A7%E6%AF%94%E6%8B%BC%EF%BC%9AGoogle%20vs.%20Amazon%20vs.%20Microsoft%20)
- [雲端平台比較：Azure、AWS、GCP](https://www.serenoclouds.com/blog/%E9%9B%B2%E7%AB%AF%E5%B9%B3%E5%8F%B0%E6%AF%94%E8%BC%83%EF%BC%9Aazure%E3%80%81aws%E3%80%81gcp/)
- [雲端平台怎麼選？比較三大雲端供應商 GCP 與 AWS 與 Azure](https://ikala.cloud/google-cloud-v-aws-v-azure/)
### [AWS](https://aws.amazon.com/tw/)
- [AWS EC2 Tutorial For Beginners | How To Use AWS | AWS EC2 Tutorial | AWS Training | Edureka AWS Live](https://www.youtube.com/watch?v=H4d3vU6-eSs&ab_channel=edureka%21)
### [GCP](https://console.cloud.google.com/?hl=zh-TW)
- [Google Cloud Platform服務介紹](https://gdgcloud-taipei.gitbook.io/google-cloud-platform-in-practice/ren-shi-google-cloud/google-cloud-platform-fu-wu-jie-shao)
## API
### [GraphQL](https://graphql.org/)
- [GraphQL 入門： 簡介 X 範例 X 優缺點](https://ithelp.ithome.com.tw/articles/10200678)
- [GraphQL 初初探](https://medium.com/@zetavg/graphql-%E5%88%9D%E5%88%9D%E6%8E%A2-2da8c3e680e6)
- [GitHub GraphQL API](https://docs.github.com/en/graphql/overview/explorer)
- [SHERlocked93/graphql-demo (build with GraphQL node.js)](https://github.com/SHERlocked93/graphql-demo)
- [8 Free to Use GraphQL APIs for Your Projects and Demos](https://www.apollographql.com/blog/community/backend/8-free-to-use-graphql-apis-for-your-projects-and-demos/)
### [XML](https://zh.wikipedia.org/zh-tw/XML)
- https://reqbin.com/req/c-yzrfjhug/curl-post-xml-example
## Database
- [System Properties Comparison Elasticsearch vs. MongoDB vs. Redis](https://db-engines.com/en/system/Elasticsearch%3BMongoDB%3BRedis)
- [DB-Engines Ranking](https://db-engines.com/en/ranking)
### [MongoDB](https://www.mongodb.com/)
- [官方手冊](https://docs.mongodb.com/manual/introduction/)
- [Github](https://github.com/mongodb/mongo)
- [該用 MySQL 或 MongoDB？選擇資料庫前你該了解的事](https://tw.alphacamp.co/blog/mysql-and-mongodb-comparison)
- [MongoDB – 為現代應用而生](http://www.omniwaresoft.com.tw/mongodb/)
- [MongoDB入門(介紹、安裝、增刪改查)](https://iter01.com/532757.html)
### [Redis](https://redis.io/)
- [快速的開放原始碼記憶體內資料存放區，可做為資料庫、快取、訊息代理程式和佇列使用。](https://aws.amazon.com/tw/redis/)
- [Github](https://github.com/redis/redis)
- [資料庫的好夥伴：Redis](https://blog.techbridge.cc/2016/06/18/redis-introduction/)

### [Elasticsearch](https://www.elastic.co/)
Elasticsearch 是一個建置在 Apache Lucene 上的分散式搜尋和分析引擎。自 2010 年發佈以來，Elasticsearch 迅速成為最熱門的搜尋引擎，常用於日誌分析、全文搜尋、安全智慧、業務分析和營運智慧使用案例。
- [什麼是Elasticsearch？– Amazon Web Services](https://aws.amazon.com/tw/opensearch-service/the-elk-stack/what-is-elasticsearch/)
- [Github](https://github.com/elastic/elasticsearch)
- [[Elasticsearch] 基本概念 & 搜尋入門](https://godleon.github.io/blog/Elasticsearch/Elasticsearch-getting-started/)
- [安裝 ElasticSearch + Kibana 實現中文全文搜尋與數據分析](https://blog.toright.com/posts/5319/fulltext-search-elasticsearch-kibana-bigdata.html)
- [ELK Stack Tutorial: What is Kibana, Logstash & Elasticsearch?](https://www.guru99.com/elk-stack-tutorial.html)
- [What is Elasticsearch and how can it be helpful?](https://marutitech.com/elasticsearch-can-helpful-business/)
- [Elasticsearch能干什么，关于Elasticsearch及实例应用](https://segmentfault.com/a/1190000022776792)
- [集中式日誌分析平臺 Elastic Stack（介紹）](https://www.itread01.com/content/1537109911.html)
## CI/CD
**C**ontinuous **I**ntegration and **C**ontinuous **D**eployment
- [Day12 什麼是 CICD](https://ithelp.ithome.com.tw/articles/10219083)
- [CI/CD 工具](https://www.fansysoft.com/blogs/-/asset_publisher/CWuRKonAWio8/blog/ci-cd)
- [一篇文章瞭解CI/CD管道全流程](https://iter01.com/595038.html)
### Git
- [為你自己學 Git](https://gitbook.tw/)
### [Jenkins](https://www.jenkins.io/)
Jenkins 是個（提供）自動化的伺服器，可用來將各種關於 building、測試、發佈、部署軟體的工作自動化。
- [[Day 27] Jenkins (1)](https://ithelp.ithome.com.tw/articles/10209290)
- [[Day 28] Jenkins (2)](https://ithelp.ithome.com.tw/articles/10209449)
- [How to Integrate Jenkins with GitHub](https://www.cprime.com/resources/blog/how-to-integrate-jenkins-github/)
### [Docker](https://www.docker.com/)
- [《Docker — 從入門到實踐》正體中文版](https://philipzheng.gitbook.io/docker_practice/)
- [學習 Docker | Microsoft](https://docs.microsoft.com/zh-tw/dotnet/architecture/containerized-lifecycle/what-is-docker)
- [Docker Web Example](https://hackmd.io/3Om0aK2OR4GMqDmNLPvI-g)
### [Kubernetes](https://kubernetes.io/)
Kubernetes（常簡稱為K8s）是用於自動部署、擴充和管理「容器化（containerized）應用程式」的開源系統。該系統由Google設計並捐贈給Cloud Native Computing Foundation（今屬Linux基金會）來使用。

它旨在提供「跨主機叢集的自動部署、擴充以及執行應用程式容器的平台」。它支援一系列容器工具，包括Docker等。
![](https://i.imgur.com/d4QLyy0.png)

- [k8s demo](./k8s.md)
## Automation Test
- [Selenium](https://www.selenium.dev/)
- [Appium](http://appium.io/)
    > Appium是一個移動端自動化測試開源工具，支援iOS和Android平臺，支援Python、Java等語言，即同一套Java或Python指令碼可以同時執行在iOS和Android平臺，Appium 是一個C/S架構，核心是一個Web伺服器，它提供了一套REST的介面。當收到客戶端的連線後，就會監聽到命令，然後在移動裝置上執行這些命令，最後將執行結果放在HTTP響應中返還給客戶端。
    - [Video demo](https://youtu.be/i1tQ1pjEFWw?t=2366)
- [Postman](https://www.postman.com/)
    >Postman 是一個可以模擬 HTTP Request 的工具，其中包含常見的 HTTP 的請求方式，例如： GET 、POST、PUT、DELETE，而它的主要功能就是能夠快速的測試你的 API 是否能夠正常的請求資料，並得到正確的請求結果。
    - [Getting Started](https://learning.postman.com/docs/getting-started/introduction/)
- [LoadNinja | Performance Testing and Load Testing Tool](https://loadninja.com/)
