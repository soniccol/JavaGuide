點擊訂閱[Java面試進階指南](https://xiaozhuanlan.com/javainterview?rel=javaguide)(專為Java面試方向準備)。[為什麼要弄這個專欄?](https://shimo.im/docs/9BJjNsNg7S4dCnz3/)

<p align="center">
<a href="https://github.com/Snailclimb/JavaGuide" target="_blank">
	<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3/logo - 副本.png" width=""/>
</a>
</p>

<p align="center">
  <a href="https://snailclimb.gitee.io/javaguide"><img src="https://img.shields.io/badge/閱讀-read-brightgreen.svg" alt="閱讀"></a>
  <a href="#聯繫我"><img src="https://img.shields.io/badge/chat-微信群-blue.svg" alt="微信群"></a>
  <a href="#公眾號"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-JavaGuide-lightgrey.svg" alt="公眾號"></a>
  <a href="#公眾號"><img src="https://img.shields.io/badge/PDF-Java面試突擊-important.svg" alt="公眾號"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/support-投稿-critical.svg" alt="投稿"></a>
</p>

<h2 align="center">Special Sponsors</h2>

<p align="center">
<a href="https://coding.net/?utm_source=JavaGuide" target="_blank">
  <img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-6/006rNwoDgy1g2dw5gau7nj30eg02vwfr.jpg"  width="390px"/>
</a>
  <a href="http://www.lubanjava.com/luban/index.html?=javaguide
" target="_blank">
  <img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-6/QQ圖片20190514211856.gif" width="390px"/>
 </a>
</p>
推薦使用 <https://snailclimb.top/JavaGuide/> 線上閱讀(存取速度慢的話，請使用 <https://snailclimb.gitee.io/javaguide> )，線上閱讀內容本倉庫同步一致。這種方式閱讀的優勢在於：有側邊欄閱讀體驗更好，Gitee pages 的存取速度相對來說也比較快。

## 目錄

- [Java](#java)
    - [基礎](#基礎)
    - [容器](#容器)
    - [併發](#併發)
    - [JVM](#jvm)
    - [I/O](#io)
    - [Java 8](#java-8)
    - [程式設計規範](#程式設計規範)
- [網路](#網路)
- [作業系統](#作業系統)
    - [Linux相關](#linux相關)
- [資料結構與演算法](#資料結構與演算法)
    - [資料結構](#資料結構)
    - [演算法](#演算法)
- [資料庫](#資料庫)
    - [MySQL](#mysql)
    - [Redis](#redis)
- [系統設計](#系統設計)
    - [設計模式(工廠模式、單例模式 ... )](#設計模式)
    - [常用框架(Spring、Zookeeper ... )](#常用框架)
    - [資料通信(訊息佇列、Dubbo ... )](#資料通信)
    - [網站架構](#網站架構)
- [面試指南](#面試指南)
    - [備戰面試](#備戰面試)
    - [常見面試題總結](#常見面試題總結)
    - [面經](#面經)
- [工具](#工具)
    - [Git](#git)
    - [Docker](#Docker)
- [資料](#資料)
    - [書單](#書單)
    - [Github榜單](#Github榜單)
- [待辦](#待辦)
- [說明](#說明)

## Java

### 基礎

* [Java 基礎知識回顧](docs/java/Java基礎知識.md)
* [J2EE 基礎知識回顧](docs/java/J2EE基礎知識.md)

### 容器

* [常見面試題](docs/java/collection/Java集合框架常見面試題.md)
* [ArrayList 源碼學習](docs/java/collection/ArrayList.md)  
* [LinkedList 源碼學習](docs/java/collection/LinkedList.md)   
* [HashMap(JDK1.8)源碼學習](docs/java/collection/HashMap.md)  

### 併發

* [Java 併發基礎常見面試題總結](docs/java/Multithread/JavaConcurrencyBasicsCommonInterviewQuestionsSummary.md)
* [Java 併發進階常見面試題總結](docs/java/Multithread/JavaConcurrencyAdvancedCommonInterviewQuestions.md)
* [併發容器總結](docs/java/Multithread/併發容器總結.md)
* [樂觀鎖與悲觀鎖](docs/essential-content-for-interview/面試必備之樂觀鎖與悲觀鎖.md)
* [JUC 中的 Atomic 原子類總結](docs/java/Multithread/Atomic.md)
* [AQS 原理以及 AQS 同步組件總結](docs/java/Multithread/AQS.md)

### JVM

* [一 Java記憶體區域](docs/java/jvm/Java記憶體區域.md)
* [二 JVM垃圾回收](docs/java/jvm/JVM垃圾回收.md)
* [三 JDK 監控和故障處理工具](docs/java/jvm/JDK監控和故障處理工具總結.md)
* [四 類檔結構](docs/java/jvm/類檔結構.md)
* [五 類載入過程](docs/java/jvm/類載入過程.md)
* [六 類載入器](docs/java/jvm/類載入器.md)

### I/O

* [BIO,NIO,AIO 總結 ](docs/java/BIO-NIO-AIO.md)
* [Java IO 與 NIO系列文章](docs/java/Java%20IO與NIO.md)

### Java 8 

* [Java 8 新特性總結](docs/java/What's%20New%20in%20JDK8/Java8Tutorial.md)
* [Java 8 學習資源推薦](docs/java/What's%20New%20in%20JDK8/Java8教程推薦.md)

### 程式設計規範

- [Java 程式設計規範](docs/java/Java程式設計規範.md)

## 網路

* [電腦網路常見面試題](docs/network/電腦網路.md)
* [電腦網路基礎知識總結](docs/network/乾貨：電腦網路知識總結.md)
* [HTTPS中的TLS](docs/network/HTTPS中的TLS.md)

## 作業系統

### Linux相關

* [後端程式師必備的 Linux 基礎知識](docs/operating-system/後端程式師必備的Linux基礎知識.md)  
* [Shell 程式設計入門](docs/operating-system/Shell.md)  

## 資料結構與演算法

### 資料結構

- [資料結構知識學習與面試](docs/dataStructures-algorithms/資料結構.md)

### 演算法

- [演算法學習資源推薦](docs/dataStructures-algorithms/演算法學習資源推薦.md)  
- [幾道常見的子符串演算法題總結 ](docs/dataStructures-algorithms/幾道常見的子符串演算法題.md)
- [幾道常見的鏈表演算法題總結 ](docs/dataStructures-algorithms/幾道常見的鏈表演算法題.md)   
- [劍指offer部分程式設計題](docs/dataStructures-algorithms/劍指offer部分程式設計題.md)
- [公司真題](docs/dataStructures-algorithms/公司真題.md)
- [回溯演算法經典案例之N皇后問題](docs/dataStructures-algorithms/Backtracking-NQueens.md)

## 資料庫

### MySQL

* [MySQL 學習與面試](docs/database/MySQL.md)
* [一千行MySQL學習筆記](docs/database/一千行MySQL命令.md)
* [MySQL高性能優化規範建議](docs/database/MySQL高性能優化規範建議.md)
* [搞定資料庫索引就是這麼簡單](docs/database/MySQL%20Index.md)
* [事務隔離級別(圖文詳解)](docs/database/事務隔離級別(圖文詳解).md)
* [一條SQL語句在MySQL中如何執行的](docs/database/一條sql語句在mysql中如何執行的.md)

### Redis

* [Redis 總結](docs/database/Redis/Redis.md)
* [Redlock分散式鎖](docs/database/Redis/Redlock分散式鎖.md)
* [如何做可靠的分散式鎖，Redlock真的可行麼](docs/database/Redis/如何做可靠的分散式鎖，Redlock真的可行麼.md)

## 系統設計

### 設計模式

- [設計模式系列文章](docs/system-design/設計模式.md)

### 常用框架

#### Spring

- [Spring 學習與面試](docs/system-design/framework/spring/Spring.md)
- [Spring 常見問題總結](docs/system-design/framework/spring/SpringInterviewQuestions.md)
- [Spring中bean的作用域與生命週期](docs/system-design/framework/spring/SpringBean.md)
- [SpringMVC 工作原理詳解](docs/system-design/framework/spring/SpringMVC-Principle.md)
- [Spring中都用到了那些設計模式?](docs/system-design/framework/spring/Spring-Design-Patterns.md)

#### ZooKeeper

- [ZooKeeper 相關概念總結](docs/system-design/framework/ZooKeeper.md)
- [ZooKeeper 資料模型和常見命令](docs/system-design/framework/ZooKeeper資料模型和常見命令.md)

### 資料通信

- [資料通信(RESTful、RPC、訊息佇列)相關知識點總結](docs/system-design/data-communication/summary.md)
- [Dubbo 總結：關於 Dubbo 的重要知識點](docs/system-design/data-communication/dubbo.md)
- [訊息佇列總結](docs/system-design/data-communication/message-queue.md)
- [RabbitMQ 入門](docs/system-design/data-communication/RabbitMQ.md)
- [RocketMQ的幾個簡單問題與答案](docs/system-design/data-communication/RocketMQ-Questions.md)

### 網站架構

- [一文讀懂分散式應該學什麼](docs/system-design/website-architecture/分散式.md)
- [8 張圖讀懂大型網站技術架構](docs/system-design/website-architecture/8%20張圖讀懂大型網站技術架構.md)
- [【面試精選】關於大型網站系統架構你不得不懂的10個問題](docs/system-design/website-architecture/【面試精選】關於大型網站系統架構你不得不懂的10個問題.md)

## 面試指南

### 備戰面試

* [【備戰面試1】程式師的簡歷就該這樣寫](docs/essential-content-for-interview/PreparingForInterview/程式師的簡歷之道.md)
* [【備戰面試2】初出茅廬的程式師該如何準備面試？](docs/essential-content-for-interview/PreparingForInterview/interviewPrepare.md)
* [【備戰面試3】7個大部分程式師在面試前很關心的問題](docs/essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)
* [【備戰面試4】Github上開源的Java面試/學習相關的倉庫推薦](docs/essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)
* [【備戰面試5】如果面試官問你“你有什麼問題問我嗎？”時，你該如何回答](docs/essential-content-for-interview/PreparingForInterview/如果面試官問你“你有什麼問題問我嗎？”時，你該如何回答.md)
* [【備戰面試6】美團面試常見問題總結（附詳解答案）](docs/essential-content-for-interview/PreparingForInterview/美團面試常見問題總結.md)

### 常見面試題總結

* [第一周（2018-8-7）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第一周（2018-8-7）.md) (為什麼 Java 中只有值傳遞、==與equals、 hashCode與equals)
* [第二周（2018-8-13）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第二周(2018-8-13).md)(String和StringBuffer、StringBuilder的區別是什麼？String為什麼是不可變的？、什麼是反射機制？反射機制的應用場景有哪些？......)
* [第三周（2018-08-22）](docs/java/collection/Java集合框架常見面試題.md) （Arraylist 與 LinkedList 異同、ArrayList 與 Vector 區別、HashMap的底層實現、HashMap 和 Hashtable 的區別、HashMap 的長度為什麼是2的冪次方、HashSet 和 HashMap 區別、ConcurrentHashMap 和 Hashtable 的區別、ConcurrentHashMap執行緒安全的具體實現方式/底層具體實現、集合框架底層資料結構總結）
* [第四周(2018-8-30).md](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第四周(2018-8-30).md) （主要內容是幾道面試常問的多執行緒基礎題。）

### 面經

- [5面阿裡,終獲offer(2018年秋招)](docs/essential-content-for-interview/BATJrealInterviewExperience/5面阿裡,終獲offer.md)
- [螞蟻金服2019實習生面經總結(已拿口頭offer)](docs/essential-content-for-interview/BATJrealInterviewExperience/螞蟻金服實習生面經總結(已拿口頭offer).md)
- [2019年螞蟻金服、頭條、拼多多的面試總結](docs/essential-content-for-interview/BATJrealInterviewExperience/2019alipay-pinduoduo-toutiao.md)

## 工具

### Git

* [Git入門](docs/tools/Git.md)

### Docker

* [Docker 入門](docs/tools/Docker.md)
* [一文搞懂 Docker 鏡像的常用操作！](docs/tools/Docker-Image.md)

## 資料

### 書單

- [Java程式師必備書單](docs/data/java-recommended-books.md)

### Github榜單

- [Java 項目月榜單](docs/github-trending/JavaGithubTrending.md)

***

## 待辦

- [x] [Java 8 新特性總結](docs/java/What's%20New%20in%20JDK8/Java8Tutorial.md)
- [x] [Java 8 新特性詳解](docs/java/What's%20New%20in%20JDK8/Java8教程推薦.md)
- [ ] Java 多執行緒類別知識重構(---正在進行中---)
- [x] [BIO,NIO,AIO 總結 ](docs/java/BIO-NIO-AIO.md)
- [ ] Netty 總結(---正在進行中---)
- [ ] 資料結構總結重構(---正在進行中---)

## 說明

### 介紹

*  **對於 Java 初學者來說：** 本文檔傾向於給你提供一個比較詳細的學習路徑，讓你對於Java整體的知識體系有一個初步認識。另外，本文的一些文章
也是你學習和複習 Java 知識不錯的實踐；
*  **對於非 Java 初學者來說：** 本文檔更適合回顧知識，準備面試，搞清面試應該把重心放在那些問題上。要搞清楚這個道理：提前知道那些面試常見，不是為了背下來應付面試，而是為了讓你可以更有針對的學習重點。

Markdown 格式參考：[Github Markdown格式](https://guides.github.com/features/mastering-markdown/)，表情素材來自：[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)。

利用 docsify 生成文檔部署在 Github pages: [docsify 官網介紹](https://docsify.js.org/#/)

### 關於轉載

如果你需要轉載本倉庫的一些文章到自己的博客的話，記得注明原文位址就可以了。

### 如何對該開來源文件進行貢獻

1. 筆記內容大多是手敲，所以難免會有筆誤，你可以幫我找錯別字。
2. 很多知識點我可能沒有涉及到，所以你可以對其他知識點進行補充。
3. 現有的知識點難免存在不完善或者錯誤，所以你可以對已有知識點的修改/補充。

### 為什麼要做這個開來源文件？

初始想法源於自己的個人那一段比較迷茫的學習經歷。主要目的是為了通過這個開源平臺來幫助一些在學習 Java 或者面試過程中遇到問題的小夥伴。

### 投稿

由於我個人能力有限，很多知識點我可能沒有涉及到，所以你可以對其他知識點進行補充。大家也可以對自己的文章進行自薦，對於不錯的文章不僅可以成功在本倉庫展示出來更可以獲得作者送出的 50 元左右的任意書籍進行獎勵(當然你也可以直接折現50元)。

### 聯繫我

添加我的微信備註“Github”,回復關鍵字 **“加群”** 即可入群。

![我的微信](https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-2/JavaGuide.jpg)

### Contributor

下面是筆主收集的一些對本倉庫提過有價值的pr或者issue的朋友，人數較多，如果你也對本倉庫提過不錯的pr或者issue的話，你可以加我的微信與我聯繫。下麵的排名不分先後！

<a href="https://github.com/fanofxiaofeng">
    <img src="https://avatars0.githubusercontent.com/u/3983683?s=460&v=4" width="45px"></a>
<a href="https://github.com/dongzl">
    <img src="https://avatars1.githubusercontent.com/u/5917359?s=460&v=4" width="45px"></a>
<a href="https://github.com/Gene1994">
    <img src="https://avatars3.githubusercontent.com/u/24930369?s=460&v=4" width="45px">
</a>
<a href="https://github.com/spikesp">
    <img src="https://avatars0.githubusercontent.com/u/12581996?s=460&v=4" width="45px"></a>
<a href="https://github.com/illusorycloud">
    <img src="https://avatars3.githubusercontent.com/u/31980412?s=460&v=4" width="45px">
</a>
<a href="https://github.com/LiWenGu">
    <img src="https://avatars0.githubusercontent.com/u/15909210?s=460&v=4" width="45px">
</a>
<a href="https://github.com/kinglaw1204">
    <img src="https://avatars1.githubusercontent.com/u/20039931?s=460&v=4" width="45px">
</a>
<a href="https://github.com/jun1st">
    <img src="https://avatars2.githubusercontent.com/u/14312378?s=460&v=4" width="45px">
</a>"
<a href="https://github.com/fantasygg">  
    <img src="https://avatars3.githubusercontent.com/u/13445354?s=460&v=4" width="45px">
</a>
<a href="https://github.com/debugjoker">  
    <img src="https://avatars3.githubusercontent.com/u/26218005?s=460&v=4" width="45px">
</a>
<a href="https://github.com/zhyank">  
    <img src="https://avatars0.githubusercontent.com/u/17696240?s=460&v=4" width="45px">
</a>
<a href="https://github.com/Goose9527">  
    <img src="https://avatars2.githubusercontent.com/u/43314997?s=460&v=4" width="45px">
</a>
<a href="https://github.com/yuechuanx">  
    <img src="https://avatars3.githubusercontent.com/u/19339293?s=460&v=4" width="45px">
</a>
<a href="https://github.com/cnLGMing">  
    <img src="https://avatars2.githubusercontent.com/u/15910705?s=460&v=4" width="45px">
</a>
<a href="https://github.com/fanchenggang">  
    <img src="https://avatars0.githubusercontent.com/u/20358122?s=460&v=4" width="45px">
</a>

### 公眾號

如果大家想要即時關注我更新的文章以及分享的乾貨的話，可以關注我的公眾號。

**《Java面試突擊》:** 由本文檔衍生的專為面試而生的《Java面試突擊》V2.0 PDF 版本[公眾號](#公眾號)後臺回復 **"Java面試突擊"** 即可免費領取！

**Java工程師必備學習資源:** 一些Java工程師常用學習資源[公眾號](#公眾號)後臺回復關鍵字 **“1”** 即可免費無套路獲取。 

![我的公眾號](https://user-gold-cdn.xitu.io/2018/11/28/167598cd2e17b8ec?w=258&h=258&f=jpeg&s=27334)
