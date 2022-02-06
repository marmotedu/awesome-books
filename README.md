# IT经典资料分享

## 分享背景

看了一些书，学了一些技术。在技术资料选择上，有一点强迫症，喜欢搜：**最好、最清** 等字样，所以平日里整理了不少精品书籍，这里做了些分类分享出来。分享分为 3 类，后期会慢慢更新：
1. **经典书籍推荐：** 会按类别推荐经典的书籍
2. **珍藏书籍推荐：** 在经典书籍中按分类推荐 1 ~ 5 本非常经典的书
3. **按标签推荐：** 比如学习微服务需要看哪些书、学习虚拟化要看哪些书、学习容器需要看哪些书

+ github 会定期更新、长期维护，也可以提 pull request，把一些精品的书籍分享出来；
+ 水平有限，里面有很多书没有看过，如有出入还请见谅，贵在分享；
+ 这些精品书都是有版权的，不是开源书籍，所以只能放豆瓣链接了（抱歉），需要 PDF 的可以网上自己搜了

Table of Contents
=================

   * [IT经典资料分享](#it经典资料分享)
      * [分享背景](#分享背景)
      * [珍藏书籍推荐](#珍藏书籍推荐)
      * [语言类](#语言类)
         * [C语言](#c语言)
            * [C基础资料](#c基础资料)
            * [C进阶资料](#c进阶资料)
            * [C网络编程](#c网络编程)
         * [C  ](#c)
         * [Java](#java)
         * [Go](#go)
         * [Python](#python)
         * [JavaScript](#javascript)
         * [NodeJS](#nodejs)
         * [PHP](#php)
         * [Perl](#perl)
         * [Ruby](#ruby)
         * [Scala](#scala)
         * [Lua](#lua)
         * [Shell](#shell)
         * [汇编语言](#汇编语言)
         * [Lisp](#lisp)
         * [正则表达式](#正则表达式)
         * [AWK](#awk)
         * [SED](#sed)
         * [HTML &amp; CSS](#html--css)
      * [计算机网络](#计算机网络)
         * [网络基础](#网络基础)
         * [TCP/IP](#tcpip)
         * [HTTP](#http)
      * [存储](#存储)
         * [存储基础](#存储基础)
         * [Ceph](#ceph)
      * [操作系统](#操作系统)
         * [操作系统基础](#操作系统基础)
         * [Linux](#linux)
         * [嵌入式](#嵌入式)
         * [Linux内核](#linux内核)
      * [防火墙](#防火墙)
      * [云计算](#云计算)
         * [系统虚拟化](#系统虚拟化)
         * [Docker](#docker)
         * [Kubernetes](#kubernetes)
         * [Serverless](#serverless)
         * [云计算基础](#云计算基础)
         * [微服务基础](#微服务基础)
         * [负载均衡](#负载均衡)
         * [服务网格](#服务网格)
      * [消息队列](#消息队列)
         * [kafka](#kafka)
         * [RabbitMQ](#rabbitmq)
      * [数据库](#数据库)
         * [SQL](#sql)
         * [MySQL](#mysql)
         * [Oracle](#oracle)
         * [Redis](#redis)
         * [Mongo](#mongo)
      * [大数据](#大数据)
         * [Hadoop](#hadoop)
         * [Spark](#spark)
         * [Flink](#flink)
         * [Hbase](#hbase)
      * [人工智能](#人工智能)
         * [人工智能基础](#人工智能基础)
         * [TensorFlow](#tensorflow)
      * [分布式](#分布式)
         * [分布式基础](#分布式基础)
         * [Etcd](#etcd)
         * [Zookpeer](#zookpeer)
      * [数据结构](#数据结构)
      * [算法](#算法)
      * [运维](#运维)
         * [运维基础](#运维基础)
         * [日志](#日志)
         * [监控告警](#监控告警)
      * [DevOps](#devops)
      * [区块链](#区块链)
      * [性能](#性能)
      * [测试](#测试)
         * [测试基础](#测试基础)
         * [性能测试](#性能测试)
      * [工具类](#工具类)
      * [面试](#面试)
      * [其它资料](#其它资料)
      * [按标签推荐系列](#按标签推荐系列)
         * [微服务系列推荐](#微服务系列推荐)
         * [云原生系列推荐](#云原生系列推荐)

## 云原生技术栈阅读材料推荐

| 类别   | 书名                                                  |
| ------ | ----------------------------------------------------- |
| 微服务 | [微服务设计](https://book.douban.com/subject/26772677 |
|   Docker     |  [《Docker 技术入门与实战》（第 3 版）](https://book.douban.com/subject/30329430/)、[《Docker ——容器与容器云》（第 2 版）](https://book.douban.com/subject/26894736/)                                                      |
|    Kubernetes    |        [Kubernetes权威指南：从Docker到Kubernetes实践全接触（第4版）](https://book.douban.com/subject/33444476/)                                               |
|     Serverless   |    [Knative Documentation](https://knative.dev/docs/)                                                     |
|   KVM     |   [KVM 虚拟化技术 : 实战与原理解析](https://book.douban.com/subject/25743939/)                                                    |
|  监控告警      |       [Prometheus Documentation](https://prometheus.io/docs/introduction/overview/)                                                 |
|   调用链     |      [Jaeger Documentation](https://www.jaegertracing.io/docs/1.26/)                                                  |
|   存储     |     [Etcd](https://time.geekbang.org/column/intro/391?tab=catalog)                                                  |
|    网关    |       [Tyk Open Source](https://tyk.io/docs/apim/open-source/)                                                |
|    消息队列    |       [Apache Kafka实战](https://book.douban.com/subject/30221096/)                                                |
|    ServiceMesh    |            [云原生服务网格Istio：原理、实践、架构与源码解析](https://book.douban.com/subject/34438220/)                                           |
|   服务发现     |    [Consul Documentation](https://www.consul.io/docs)                                                   |
| 网络       |       [Cilium Documentation](https://docs.cilium.io/)                                                 |

## 珍藏书籍推荐

**每种分类推荐 1 ~ 5 本需要珍藏书籍：**

> 因为个人爱好、水平优先，推荐的书可能也不一样，不服预期，大佬勿喷，可以留言，我会修正 :-)

|类别|书籍|豆瓣读书链接|
|----|----|----|
|C|C程序设计(第五版)<br>C程序设计语言(第2版)<br>GNU/LINUX环境编程(第2版)<br>UNIX环境高级编程(第3版)<br>C和指针<br>C专家编程<br>Linux网络编程（第2版）<br>UNIX网络编程卷1：套接字联网API（第3版）<br>LNIX网络编程卷2：进程间通信（第2版）|https://book.douban.com/subject/30385709/<br>https://book.douban.com/subject/1139336/<br>https://book.douban.com/subject/4725273/<br>https://book.douban.com/subject/25900403/<br>https://book.douban.com/subject/3012360/<br>https://book.douban.com/subject/2377310/<br>https://book.douban.com/subject/26669330/<br>https://book.douban.com/subject/4859464/<br>https://book.douban.com/subject/4886882/|
|C++|C++程序设计教程（第2版）<br>C++程序设计语言（第1-4部分）<br>C++ Primer Plus（第6版）<br>C++编程思想（两卷合订本）|https://book.douban.com/subject/1444656/<br>https://book.douban.com/subject/26857943/<br>https://book.douban.com/subject/10789789/<br>https://book.douban.com/subject/6558198/|
|Java|Java编程思想（第4版）|https://book.douban.com/subject/2130190/|
|Go|Go程序设计语言<br>Go语言编程|https://book.douban.com/subject/27044219/<br>https://book.douban.com/subject/11577300/|
|Python|Python基础教程（第3版）<br>Python核心编程（第3版）|https://book.douban.com/subject/27667375/<br>https://book.douban.com/subject/26801374/|
|JavaScript|JavaScript高级程序设计（第3版）<br>JavaScript权威指南（第6版）|https://book.douban.com/subject/10549733/<br>https://book.douban.com/subject/10546125/|
|NodeJS|深入浅出Node.js<br>Node.js高级编程|https://book.douban.com/subject/25768396/<br>https://book.douban.com/subject/25799431/|
|PHP|PHP与MySQL程序设计（第4版）|https://book.douban.com/subject/6516132/|
|Perl|Perl语言入门（第5版）|https://book.douban.com/subject/4088038/|
|Ruby|Ruby元编程（第2版）|https://book.douban.com/subject/26575429/|
|Scala|Scala编程（第3版）<br>Scala程序设计（第2版）|https://book.douban.com/subject/27591387/<br>https://book.douban.com/subject/26740545/|
|Lua|Lua程序设计（第2版）|https://book.douban.com/subject/3076942/|
|Shell|实战Linux Shell编程与服务器管理<br>Shell脚本专家指南|https://book.douban.com/subject/4722707/<br>https://book.douban.com/subject/4935288/|
|汇编语言|汇编语言（第3版）|https://item.jd.com/12259774.html?dist=jd|
|Lisp|实用Common Lisp编程|https://book.douban.com/subject/6859720/|
|正则表达式|正则指引（第2版）<br>精通正则表达式（第3版）|https://book.douban.com/subject/30352656/<br>https://book.douban.com/subject/2154713/|
|AWK|sed与awk（第3版）|https://book.douban.com/subject/1236944/|
|Sed|sed与awk（第3版）|https://book.douban.com/subject/1236944/|
|HTML & CSS|CSS权威指南（中文第3版）<br>HTML5权威指南|https://book.douban.com/subject/2308234/<br>https://book.douban.com/subject/25786074/|
|计算机网络|计算机网络（第7版）|https://book.douban.com/subject/26960678/|
|TCP/IP|图解TCP/IP（第5版）<br>TCP/IP详解 卷1：协议（第2版）|https://book.douban.com/subject/24737674/<br>https://book.douban.com/subject/26825411/|
|HTTP|图解HTTP<br>HTTP权威指南|https://book.douban.com/subject/25863515/<br>https://book.douban.com/subject/10746113/|
|操作系统基础|计算机操作系统（第3版）<br>计算机系统概论（第2版）|https://book.douban.com/subject/1058576/<br>https://book.douban.com/subject/2185076/|
|Linux|鸟哥的Linux私房菜:基础学习篇(第4版)<br>循序渐进Linux（第2版） : 基础知识 服务器搭建 系统管理 性能调优 虚拟化与集群应用|https://book.douban.com/subject/30359954/<br>https://book.douban.com/subject/26758194/|
|嵌入式|嵌入式Linux设备驱动开发详解|https://book.douban.com/subject/2985887/|
|Linux 内核|Linux内核设计与实现（原书第3版）<br>LINUX内核源代码情景分析（全册）<br>深入理解LINUX内核（第3版）<br>LINUX设备驱动程序（第3版）<br>Linux内核完全注释（修订版）<br>深入Linux内核架构<br>|https://book.douban.com/subject/6097773/<br>https://book.douban.com/subject/1231584/<br>https://book.douban.com/subject/2287506/<br>https://book.douban.com/subject/1420480/<br>https://book.douban.com/subject/1231236/<br>https://book.douban.com/subject/4843567/|
|内核存储|Linux 内核模块编程<br>Linux内核探秘：深入解析文件系统和设备驱动的架构与设计<br>存储技术原理分析：基于 Linux_2.6 内核源代码<br>LINUX 设备驱动程序(第 3 版)|这本没有书籍，但是编写内核模块的经典Hello World入门书籍<br>https://book.douban.com/subject/25817503/<br>https://book.douban.com/subject/6822367/<br>https://book.douban.com/subject/1420480/|
|防火墙|Linux防火墙-(原书第3版)|https://book.douban.com/subject/1838749/|
|虚拟化原理|系统虚拟化 : 原理与实现|https://book.douban.com/subject/3619896/|
|KVM|KVM虚拟化技术 : 实战与原理解析|https://book.douban.com/subject/25743939/|
|Docker|Docker技术入门与实战（第3版）<br>Docker 容器与容器云（第2版）|https://book.douban.com/subject/30329430/<br>https://book.douban.com/subject/26894736/|
|Kubernetes|Kubernetes权威指南：从Docker到Kubernetes实践全接触（第4版）<br>基于Kubernetes的容器云平台实战|https://book.douban.com/subject/33444476/<br>https://book.douban.com/subject/30333237/|
|Serverless|Serverless架构：从原理、设计到项目实战<br>Serverless架构：无服务器应用与AWS Lambda|我们团队刘宇大佬写的一本书，没有盗版PDF<br>https://book.douban.com/subject/30290516/|
|微服务|微服务架构与实践（第1版）<br>微服务设计|https://book.douban.com/subject/26693152/<br>https://book.douban.com/subject/26772677/|
|ServiceMesh|云原生服务网格Istio：原理、实践、架构与源码解析|https://book.douban.com/subject/34438220/|
|kafka|Apache Kafka实战<br>Apache Kafka源码剖析<br>Kafka权威指南|https://book.douban.com/subject/30221096/<br>https://book.douban.com/subject/27038473/<br>https://book.douban.com/subject/27665114/|
|RabbitMQ|RabbitMQ实战 : 高效部署分布式消息队列|https://book.douban.com/subject/26649178/|
|SQL|精通SQL结构化查询语言详解|https://book.douban.com/subject/2022427/|
|MySQL|MySQL技术内幕InnoDB存储引擎（第1版）<br>MySQL必知必会|https://book.douban.com/subject/5373022/<br>https://book.douban.com/subject/3354490/|
|Oracle|Oracle 10g数据库管理应用与开发标准教程|https://book.douban.com/subject/2316500/|
|Redis|Redis设计与实现|https://book.douban.com/subject/25900156/|
|Mongo|MongoDB大数据处理权威指南（第2版）|https://book.douban.com/subject/26269829/|

----

## 语言类

### C语言

#### C基础资料
|书名|豆瓣读书链接|
|----|----|
|[C程序设计(第五版)](https://book.douban.com/subject/30385709/)<br>[C程序设计(第四版)](https://book.douban.com/subject/4864940/)|https://book.douban.com/subject/30385709/<br>https://book.douban.com/subject/4864940/|
|[The C Programming language](https://book.douban.com/subject/1236999/)|https://book.douban.com/subject/1236999/|
|[C程序设计语言(第2版)](https://book.douban.com/subject/1139336/)|https://book.douban.com/subject/1139336/|
|[一站式学习C编程](https://book.douban.com/subject/6025290/)|https://book.douban.com/subject/6025290/|
|[C Primer Plus（第6版）](https://book.douban.com/subject/26792521/)|https://book.douban.com/subject/26792521/|

#### C进阶资料
|书名|豆瓣读书链接|
|----|----|
|[UNIX环境高级编程(第3版)](https://book.douban.com/subject/25900403/)|https://book.douban.com/subject/25900403/|
|[C和指针](https://book.douban.com/subject/3012360/)|https://book.douban.com/subject/3012360/|
|[C陷阱与缺陷](https://book.douban.com/subject/1102097/)|https://book.douban.com/subject/1102097/|
|[C专家编程](https://book.douban.com/subject/2377310/)|https://book.douban.com/subject/2377310/|
|[GNU/LINUX环境编程(第2版)](https://book.douban.com/subject/4725273/)|https://book.douban.com/subject/4725273/|
|[GNU/Linux 编程指南(第2版)](https://book.douban.com/subject/1231823/)|https://book.douban.com/subject/1231823/|
|[Linux/UNIX系统编程手册（上册）](https://book.douban.com/subject/25809330/)|https://book.douban.com/subject/25809330/|
|[Linux/UNIX系统编程手册（下册）](https://book.douban.com/subject/25809330/)|https://book.douban.com/subject/25809330/|
|[Linux程序设计（第4版）](https://book.douban.com/subject/4831448/)|https://book.douban.com/subject/4831448/|
|[Linux系统编程（第2版）](https://book.douban.com/subject/25906154/)|https://book.douban.com/subject/25906154/|

#### C网络编程
|书名|豆瓣读书链接|
|----|----|
|[Linux网络编程（第2版）](https://book.douban.com/subject/26669330/)|https://book.douban.com/subject/26669330/|
|[UNIX网络编程卷1：套接字联网API（第3版）](https://book.douban.com/subject/4859464/)|https://book.douban.com/subject/4859464/|
|[UNIX网络编程卷2：进程间通信（第2版）](https://book.douban.com/subject/4886882/)|https://book.douban.com/subject/4886882/|

### C++
|书名|豆瓣读书链接|
|----|----|
|[C++ Primer Plus（第6版）](https://book.douban.com/subject/10789789/)|https://book.douban.com/subject/10789789/|
|[Effective C++（中文第3版）](https://book.douban.com/subject/1842426/)|https://book.douban.com/subject/1842426/|
|[C++程序设计（第2版）](https://book.douban.com/subject/1174290/)|https://book.douban.com/subject/1174290/|
|[C++程序设计教程（第2版）](https://book.douban.com/subject/1444656/)|https://book.douban.com/subject/1444656/|
|[C++编程思想（两卷合订本）](https://book.douban.com/subject/6558198/)|https://book.douban.com/subject/6558198/|
|[C++高级编程(中文第3版)](https://book.douban.com/subject/26378198/)|https://book.douban.com/subject/26378198/|
|[C++高级编程(英文第4版)](https://book.douban.com/subject/30189176/)|https://book.douban.com/subject/30189176/|
|[C++性能优化指南](https://book.douban.com/subject/27666339/)|https://book.douban.com/subject/27666339/|
|[C++沉思录（第2版）](https://book.douban.com/subject/2970056/)|https://book.douban.com/subject/2970056/|
|[C++程序设计语言（第1-4部分）](https://book.douban.com/subject/26857943/)|https://book.douban.com/subject/26857943/|

### Java
|书名|豆瓣读书链接|
|----|----|
|[Java编程思想（第4版）](https://book.douban.com/subject/2130190/)|https://book.douban.com/subject/2130190/|
|[深入理解Java虚拟机（第2版）：JVM高级特性与最佳实践](https://book.douban.com/subject/24722612/)|https://book.douban.com/subject/24722612/|
|[Java从入门到精通（第4版）](https://book.douban.com/subject/26900033/)|https://book.douban.com/subject/26900033/|
|[Java并发编程实战](https://book.douban.com/subject/10484692/)|https://book.douban.com/subject/10484692/|
|[Java并发编程的艺术](https://book.douban.com/subject/26591326/)|https://book.douban.com/subject/26591326/|
|[深入浅出Spring Boot 2.x](https://book.douban.com/subject/30323325/)|https://book.douban.com/subject/30323325/|
|[Spring Boot实战](https://book.douban.com/subject/26857423/)|https://book.douban.com/subject/26857423/|
|[Java函数式编程](https://book.douban.com/subject/27594722/)|https://book.douban.com/subject/27594722/|
|[Java 8函数式编程](https://book.douban.com/subject/26346017/)|https://book.douban.com/subject/26346017/|
|[Java Web高级编程 : 涵盖WebSockets、Spring Framework、JPA Hibernate和Spring Security](https://book.douban.com/subject/26581686/)|https://book.douban.com/subject/26581686/|
|[Java性能权威指南](https://book.douban.com/subject/26740520/)|https://book.douban.com/subject/26740520/|
|[实战Java高并发程序设计（第2版）](https://book.douban.com/subject/30358019/)|https://book.douban.com/subject/30358019/|
|[Java Nio](https://book.douban.com/subject/1433583/)|https://book.douban.com/subject/1433583/|


### Go

|书名|豆瓣读书链接|
|----|----|
|[Go程序设计语言](https://book.douban.com/subject/27044219/)|https://book.douban.com/subject/27044219/|
|[Go语言编程](https://book.douban.com/subject/11577300/)|https://book.douban.com/subject/11577300/|
|[Go 并发编程实战（第2版）](https://book.douban.com/subject/27016236/)|https://book.douban.com/subject/27016236/|
|[Go 语言实战](https://book.douban.com/subject/27015617/)|https://book.douban.com/subject/27015617/|
|[Go语言程序设计](https://book.douban.com/subject/24869910/)|https://book.douban.com/subject/24869910/|
|[Go语言学习笔记]()|https://book.douban.com/subject/26832468/|
|[Go语言编程入门与实战技巧](https://book.douban.com/subject/30325764/)|https://book.douban.com/subject/30325764/|
|[Go语言圣经（中文版）](https://book.douban.com/subject/26859123/)|https://book.douban.com/subject/26859123/|
|[Go语言核心编程](https://book.douban.com/subject/30351288/)|https://book.douban.com/subject/30351288/|
|[Go Web编程](https://book.douban.com/subject/27204133/)|https://book.douban.com/subject/27204133/|


### Python
|书名|豆瓣读书链接|
|----|----|
|[Python基础教程（第3版）](https://book.douban.com/subject/27667375/)|https://book.douban.com/subject/27667375/|
|[Python核心编程（第3版）](https://book.douban.com/subject/26801374/)|https://book.douban.com/subject/26801374/|
|[Python高级编程（第2版）](https://book.douban.com/subject/27133480/)|https://book.douban.com/subject/27133480/|
|[Python学习手册（中文第4版）](https://book.douban.com/subject/6049132/)|https://book.douban.com/subject/6049132/|
|[Python学习手册（英文第5版）](https://book.douban.com/subject/22139956/)|https://book.douban.com/subject/22139956/|
|[Python编程（第4版，上下册）](https://book.douban.com/subject/26314833/)|https://book.douban.com/subject/26314833/|
|[Python Cookbook（中文第2版）](https://book.douban.com/subject/4828875/)|https://book.douban.com/subject/4828875/|
|[Python高性能编程](https://book.douban.com/subject/27064848/)|https://book.douban.com/subject/27064848/|
|[Python自然语言处理（中文版）](https://book.douban.com/subject/5336893/)|https://book.douban.com/subject/5336893/|
|[Python For Data Analysis（英文）](https://book.douban.com/subject/10760444/)|https://book.douban.com/subject/10760444/|


### JavaScript
|书名|豆瓣读书链接|
|----|----|
|[JavaScript模式 ](https://book.douban.com/subject/11506062/)|https://book.douban.com/subject/11506062/|
|[JavaScript设计模式与开发实践](https://book.douban.com/subject/26382780/)|https://book.douban.com/subject/26382780/|
|[JavaScript权威指南（第6版）](https://book.douban.com/subject/10549733/)|https://book.douban.com/subject/10549733/|
|[JavaScript高级程序设计（第3版）](https://book.douban.com/subject/10546125/)|https://book.douban.com/subject/10546125/|
|[JavaScript设计模式](https://book.douban.com/subject/3329540/)|https://book.douban.com/subject/3329540/|
|[JavaScript学习指南（第2版）](https://book.douban.com/subject/4089837/)|https://book.douban.com/subject/4089837/|
|[JavaScript设计模式与开发实践](https://book.douban.com/subject/26382780/)|https://book.douban.com/subject/26382780/|
|[JavaScript DOM编程艺术（第2版）](https://book.douban.com/subject/6038371/)|https://book.douban.com/subject/6038371/|
|[JavaScript忍者秘籍（第2版）](https://book.douban.com/subject/26638316/)|https://book.douban.com/subject/26638316/|
|[JavaScript语言精粹](https://book.douban.com/subject/3590768/)|https://book.douban.com/subject/3590768/|
|[JavaScript经典实例（第2版）](https://book.douban.com/subject/26773411/)|https://book.douban.com/subject/26773411/|
|[JavaScript编程全解](https://book.douban.com/subject/25767719/)|https://book.douban.com/subject/25767719/|
|[JavaScript编程精解（第2版）](https://book.douban.com/subject/26707144/)|https://book.douban.com/subject/26707144/|
|[学习JavaScript数据结构与算法](https://book.douban.com/subject/25945449/)|https://book.douban.com/subject/25945449/|
|[JavaScript函数式编程](https://book.douban.com/subject/26579320/)|https://book.douban.com/subject/26579320/|
|[JavaScript从入门到精通（标准版）](https://book.douban.com/subject/11534729/)|https://book.douban.com/subject/11534729/|
|[数据结构与算法JavaScript描述](https://book.douban.com/subject/25945449/)|https://book.douban.com/subject/25945449/|
|[JavaScript开发技术大全](https://book.douban.com/subject/3120941/)|https://book.douban.com/subject/3120941/|

### NodeJS
|书名|豆瓣读书链接|
|----|----|
|[深入浅出Node.js](https://book.douban.com/subject/25768396/)|https://book.douban.com/subject/25768396/|
|[Node.js 实战](https://book.douban.com/subject/25870705/)|https://book.douban.com/subject/25870705/|
|[Node.js实战（第2版）](https://book.douban.com/subject/30288107/)|https://book.douban.com/subject/30288107/|
|[Node.js权威指南](https://book.douban.com/subject/25892704/)|https://book.douban.com/subject/25892704/|
|[Node.js开发指南](https://book.douban.com/subject/10789820/)|https://book.douban.com/subject/10789820/|
|[Node.js高级编程](https://book.douban.com/subject/25799431/)|https://book.douban.com/subject/25799431/|
|[Node.js进阶之路](https://book.douban.com/subject/26970060/)|https://book.douban.com/subject/26970060/|
|[了不起的Node.js 将JavaScript进行到底](https://book.douban.com/subject/25767596/)|https://book.douban.com/subject/25767596/|


### PHP
|书名|豆瓣读书链接|
|----|----|
|[PHP与MySQL程序设计（第4版）](https://book.douban.com/subject/6516132/)|https://book.douban.com/subject/6516132/|
|[Modern PHP（中文版）](https://book.douban.com/subject/26635862/)|https://book.douban.com/subject/26635862/|
|[Modern PHP（英文版）](https://book.douban.com/subject/25982663/)|https://book.douban.com/subject/25982663/|
|[PHP高性能开发：基础、框架与项目实战](https://book.douban.com/subject/30769463/)|https://book.douban.com/subject/30769463/|
|[深入PHP：面向对象、模式与实践（第3版）](https://book.douban.com/subject/6559267/)|https://book.douban.com/subject/6559267/|


### Perl
|书名|豆瓣读书链接|
|----|----|
|[Perl语言入门（第5版](https://book.douban.com/subject/4088038/)|https://book.douban.com/subject/4088038/|
|[Perl高效编程（第2版）](https://book.douban.com/subject/30549490/)|https://book.douban.com/subject/30549490/|
|[PERL实例精解（第4版）](https://book.douban.com/subject/3335419/)|https://book.douban.com/subject/3335419/|

### Ruby
|书名|豆瓣读书链接|
|----|----|
|[Ruby元编程（第2版）](https://book.douban.com/subject/26575429/)|https://book.douban.com/subject/26575429/|


### Scala
|书名|豆瓣读书链接|
|----|----|
|[Scala编程](https://book.douban.com/subject/5377415/)|https://book.douban.com/subject/5377415/|
|[Scala编程（第3版）](https://book.douban.com/subject/27591387/)|https://book.douban.com/subject/27591387/|
|[Scala程序设计（第2版）](https://book.douban.com/subject/26740545/)|https://book.douban.com/subject/26740545/|

### Lua

|书名|豆瓣读书链接|
|----|----|
|[Lua程序设计（第2版](https://book.douban.com/subject/3076942/)|https://book.douban.com/subject/3076942/|

### Shell
|书名|豆瓣读书链接|
|----|----|
|[实战Linux Shell编程与服务器管理](https://book.douban.com/subject/4722707/)|https://book.douban.com/subject/4722707/|
|[Shell脚本专家指南](https://book.douban.com/subject/4935288/)|https://book.douban.com/subject/4935288/|
|[Linux命令行与shell脚本编程大全(第3版)](https://book.douban.com/subject/26854226/)|https://book.douban.com/subject/26854226/|
|[Linux Shell命令行及脚本编程实例详解](https://book.douban.com/subject/26752891/)|https://book.douban.com/subject/26752891/|
|[Linux系统命令及Shell脚本实践指南](https://book.douban.com/subject/25803528/)|https://book.douban.com/subject/25803528/|
|[Shell从入门到精通（第2版）](https://book.douban.com/subject/25886372/)|https://book.douban.com/subject/25886372/|
|[Linux Shell脚本攻略（第3版）](https://book.douban.com/subject/30172987/)|https://book.douban.com/subject/30172987/|
|[Linux Shell编程从初学到精通](https://book.douban.com/subject/5988663/)|https://book.douban.com/subject/5988663/|

### 汇编语言
|书名|豆瓣读书链接|
|----|----|
|[汇编语言（第3版](https://item.jd.com/12259774.html?dist=jd)|https://item.jd.com/12259774.html?dist=jd|
|[Professional Assembly Language（中文）](https://book.douban.com/subject/1446250/)|https://book.douban.com/subject/1446250/|
|[Professional Assembly Language（英文）](https://book.douban.com/subject/2039913/)|https://book.douban.com/subject/2039913/|
|[汇编语言：基于x86处理器（第7版）](https://book.douban.com/subject/26769528/)|https://book.douban.com/subject/26769528/|
|[Intel汇编语言程序设计](https://book.douban.com/subject/2250326/)|https://book.douban.com/subject/2250326/|
|[Windows环境下32位汇编语言程序设计（第2版）](https://book.douban.com/subject/1783103/)|https://book.douban.com/subject/1783103/|
|[Windows环境下32位汇编语言程序设计（典藏版）](https://book.douban.com/subject/24846626/)|https://book.douban.com/subject/24846626/|

### Lisp
|书名|豆瓣读书链接|
|----|----|
|[实用Common Lisp编程](https://book.douban.com/subject/6859720/)|https://book.douban.com/subject/6859720/|

### 正则表达式
|书名|豆瓣读书链接|
|----|----|
|[正则指引（第2版）](https://book.douban.com/subject/30352656/)|https://book.douban.com/subject/30352656/|
|[精通正则表达式（第3版）](https://book.douban.com/subject/2154713/)|https://book.douban.com/subject/2154713/|
|[正则表达式必知必会](https://book.douban.com/subject/2269648/)|https://book.douban.com/subject/2269648/|
|[学习正则表达式](https://book.douban.com/subject/22601258/)|https://book.douban.com/subject/22601258/|

### AWK
|书名|豆瓣读书链接|
|----|----|
|[sed与awk（第3版](https://book.douban.com/subject/1236944/)|https://book.douban.com/subject/1236944/|
|[Effective awk Programming（英文）](https://book.douban.com/subject/26257265/)|https://book.douban.com/subject/26257265/|

### SED
|书名|豆瓣读书链接|
|----|----|
|[sed与awk（第3版）](https://book.douban.com/subject/1236944/)|https://book.douban.com/subject/1236944/|

### HTML & CSS
|书名|豆瓣读书链接|
|----|----|
|[CSS权威指南（中文第3版）](https://book.douban.com/subject/2308234/)|https://book.douban.com/subject/2308234/|
|[HTML5权威指南](https://book.douban.com/subject/25786074/)|https://book.douban.com/subject/25786074/|
|[HTML5+CSS3从入门到精通](https://book.douban.com/subject/24708139/)|https://book.douban.com/subject/24708139/|
|[HTML5与CSS3基础教程（第8版）](https://book.douban.com/subject/25878992/)|https://book.douban.com/subject/25878992/|
|[HTML5程序设计（第2版）](https://book.douban.com/subject/10608238/)|https://book.douban.com/subject/10608238/|
|[CSS Web设计高级教程](https://book.douban.com/subject/3879846/)|https://book.douban.com/subject/3879846/|


## 计算机网络

### 网络基础
|书名|豆瓣读书链接|
|----|----|
|[计算机网络（第7版）](https://book.douban.com/subject/26960678/)|https://book.douban.com/subject/26960678/|
|[计算机网络：自顶向下方法(第6版)](https://book.douban.com/subject/26176870/)|https://book.douban.com/subject/26176870/|
|[精通Linux内核网络](https://book.douban.com/subject/26420010/)|https://book.douban.com/subject/26420010/|
|[网络工程师教程（第5版）](https://book.douban.com/subject/30866578/)|https://book.douban.com/subject/30866578/|


### TCP/IP
|书名|豆瓣读书链接|
|----|----|
|[TCP/IP详解 卷1：协议（第2版）](https://book.douban.com/subject/26825411/)|https://book.douban.com/subject/26825411/|
|[图解TCP/IP（第5版）](https://book.douban.com/subject/24737674/)|https://book.douban.com/subject/24737674/|
|[TCP/IP网络编程](https://book.douban.com/subject/25911735/)|https://book.douban.com/subject/25911735/|
|[TCP/IP Sockets编程 : C语言实现（第2版）](https://book.douban.com/subject/4124130/)|https://book.douban.com/subject/4124130/|
|[TCP/IP协议族(第4版)](https://book.douban.com/subject/26220771/)|https://book.douban.com/subject/26220771/|
|[TCP/IP入门经典（第5版）](https://book.douban.com/subject/10556677/)|https://book.douban.com/subject/10556677/|


### HTTP
|书名|豆瓣读书链接|
|----|----|
|[HTTP权威指南](https://book.douban.com/subject/10746113/)|https://book.douban.com/subject/10746113/|
|[图解HTTP](https://book.douban.com/subject/25863515/)|https://book.douban.com/subject/25863515/|
|[图解网络硬件](https://book.douban.com/subject/25919428/)|https://book.douban.com/subject/25919428/|
|[HTTP/2基础教程](https://book.douban.com/subject/27665112/)|https://book.douban.com/subject/27665112/|
|[HTTPS权威指南：在服务器和Web应用上部署SSL-TLS和PKI](https://book.douban.com/subject/26869219/)|https://book.douban.com/subject/26869219/|


## 存储
### 存储基础
|书名|豆瓣读书链接|
|----|----|
|[软件定义存储：原理、实践与生态](https://book.douban.com/subject/26831614/)|https://book.douban.com/subject/26831614/|
|[大规模分布式存储系统 : 原理解析与架构实战](https://book.douban.com/subject/25723658/)|https://book.douban.com/subject/25723658/|

### Ceph
|书名|豆瓣读书链接|
|----|----|
|[Ceph分布式存储学习指南](https://book.douban.com/subject/27019132/)|https://book.douban.com/subject/27019132/|
|[Ceph设计原理与实现](https://book.douban.com/subject/27178824/)|https://book.douban.com/subject/27178824/|
|[Ceph分布式存储实战](https://book.douban.com/subject/26937692/)|https://book.douban.com/subject/26937692/|


## 操作系统

### 操作系统基础
|书名|豆瓣读书链接|
|----|----|
|[计算机系统概论（第2版）](https://book.douban.com/subject/2185076/)|https://book.douban.com/subject/2185076/|
|[深入理解计算机系统（原书第3版）](https://book.douban.com/subject/26912767/)|https://book.douban.com/subject/26912767/|
|[操作系统概念（第7版）](https://book.douban.com/subject/4289836/)|https://book.douban.com/subject/4289836/|
|[计算机操作系统（第3版）](https://book.douban.com/subject/1058576/)|https://book.douban.com/subject/1058576/|
|[操作系统-精髓与设计原理（第8版）](https://book.douban.com/subject/26993995/)|https://book.douban.com/subject/26993995/|
|[现代操作系统（第4版）](https://book.douban.com/subject/27096665/)|https://book.douban.com/subject/27096665/|
|[计算机组成与设计-硬件软件接口（第5版）](https://book.douban.com/subject/26604008/)|https://book.douban.com/subject/26604008/|
|[操作系统设计与实现(第三版，上册)](https://book.douban.com/subject/2044818/)|https://book.douban.com/subject/2044818/|

### Linux
|书名|豆瓣读书链接|
|----|----|
|[鸟哥的Linux私房菜:基础学习篇(第4版)](https://book.douban.com/subject/30359954/)|https://book.douban.com/subject/30359954/|
|[循序渐进Linux（第2版） : 基础知识 服务器搭建 系统管理 性能调优 虚拟化与集群应用](https://book.douban.com/subject/26758194/)|https://book.douban.com/subject/26758194/|
|[深度探索Linux操作系统 : 系统构建和原理解析](https://book.douban.com/subject/25743846/)|https://book.douban.com/subject/25743846/|
|[Linux系统管理技术手册（第2版）](https://book.douban.com/subject/3042029/)|https://book.douban.com/subject/3042029/|
|[高性能Linux服务器构建实战：运维监控、性能调优与集群应用](https://book.douban.com/subject/7564094/)|https://book.douban.com/subject/7564094/|
|[Linux安全体系分析与编程](https://book.douban.com/subject/2306842/)|https://book.douban.com/subject/2306842/|
|[Linux玩家技术宝典 : 你所不知道的Linux](https://book.douban.com/subject/4027707/)|https://book.douban.com/subject/4027707/|
|[Red Hat Linux安全与优化](https://book.douban.com/subject/1237488/)|https://book.douban.com/subject/1237488/|

### 嵌入式
|书名|豆瓣读书链接|
|----|----|
|[嵌入式Linux程序设计案例与实验教程](https://book.douban.com/subject/3670713/)|https://book.douban.com/subject/3670713/|
|[构建嵌入式Linux核心软件系统实战 : 构建嵌入式Linux核心软件系统实战](https://book.douban.com/subject/24522809/)|https://book.douban.com/subject/24522809/|
|[嵌入式Linux应用开发完全手册](https://book.douban.com/subject/3152027/)|https://book.douban.com/subject/3152027/|
|[嵌入式Linux设备驱动开发详解](https://book.douban.com/subject/2985887/)|https://book.douban.com/subject/2985887/|
|[深入浅出嵌入式底层软件开发](https://book.douban.com/subject/6533463/)|https://book.douban.com/subject/6533463/|

### Linux内核
|书名|豆瓣读书链接|
|----|----|
|[Linux内核设计与实现（原书第3版）](https://book.douban.com/subject/6097773/)|https://book.douban.com/subject/6097773/|
|[深入理解LINUX内核（第3版）](https://book.douban.com/subject/2287506/)|https://book.douban.com/subject/2287506/|
|[Linux内核设计的艺术 : 图解Linux操作系统架构设计与实现原理](https://book.douban.com/subject/6433169/)|https://book.douban.com/subject/6433169/|
|[LINUX设备驱动程序（第3版）](https://book.douban.com/subject/1420480/)|https://book.douban.com/subject/1420480/|
|[Linux设备驱动开发详解 : 基于最新的Linux 4.0内核](https://book.douban.com/subject/26600201/)|https://book.douban.com/subject/26600201/|
|[Linux设备驱动开发详解（第2版）](https://book.douban.com/subject/5351818/)|https://book.douban.com/subject/5351818/|
|[深入Linux内核架构](https://book.douban.com/subject/4843567/)|https://book.douban.com/subject/4843567/|
|[Linux内核精髓 : 精通Linux内核必会的75个绝技](https://book.douban.com/subject/21332497/)|https://book.douban.com/subject/21332497/|
|[Linux内核完全注释（修订版）](https://book.douban.com/subject/1231236/)|https://book.douban.com/subject/1231236/|
|[深入Linux设备驱动程序内核机制](https://book.douban.com/subject/10433743/)|https://book.douban.com/subject/10433743/|
|[深入理解LINUX网络技术内幕](https://book.douban.com/subject/4015134/)|https://book.douban.com/subject/4015134/|
|[Linux驱动程序开发实例](https://book.douban.com/subject/6078728/)|https://book.douban.com/subject/6078728/|


## 防火墙
|书名|豆瓣读书链接|
|----|----|
|[Linux防火墙-(原书第3版)](https://book.douban.com/subject/1838749/)|https://book.douban.com/subject/1838749/|
|[Linux防火墙](https://book.douban.com/subject/3678862/)|https://book.douban.com/subject/3678862/|


## 云计算

### 系统虚拟化
|书名|豆瓣读书链接|
|----|----|
|[Xen虚拟化技术](https://book.douban.com/subject/3768550/)|https://book.douban.com/subject/3768550/|
|[KVM虚拟化技术 : 实战与原理解析](https://book.douban.com/subject/25743939/)|https://book.douban.com/subject/25743939/|
|[Linux KVM虚拟化架构实战指南](https://book.douban.com/subject/26766965/)|https://book.douban.com/subject/26766965/|
|[系统虚拟化 : 原理与实现](https://book.douban.com/subject/3619896/)|https://book.douban.com/subject/3619896/|
|[虚拟化技术原理与实现](https://book.douban.com/subject/19986436/)|https://book.douban.com/subject/19986436/|

### Docker
|书名|豆瓣读书链接|
|----|----|
|[Docker 容器与容器云（第2版）](https://book.douban.com/subject/26894736/)|https://book.douban.com/subject/26894736/|
|[Docker技术入门与实战（第3版）](https://book.douban.com/subject/30329430/)|https://book.douban.com/subject/30329430/|
|[Docker 源码分析](https://book.douban.com/subject/26581184/)|https://book.douban.com/subject/26581184/|
|[Docker开发指南](https://book.douban.com/subject/27013734/)|https://book.douban.com/subject/27013734/|

### Kubernetes
|书名|豆瓣读书链接|
|----|----|
|[Kubernetes权威指南：从Docker到Kubernetes实践全接触（第4版）](https://book.douban.com/subject/33444476/)|https://book.douban.com/subject/33444476/|
|[开源容器云OpenShift构建基于Kubernetes的企业应用云平台](https://book.douban.com/subject/27088186/)|https://book.douban.com/subject/27088186/|
|[基于Kubernetes的容器云平台实战](https://book.douban.com/subject/30333237/)|https://book.douban.com/subject/30333237/|

### Serverless
|书名|豆瓣读书链接|
|----|----|
|[Serverless架构：无服务器应用与AWS Lambda](https://book.douban.com/subject/30290516/)|https://book.douban.com/subject/30290516/|

### 云计算基础
|书名|豆瓣读书链接|
|----|----|
|[数据中心虚拟化技术权威指南](https://book.douban.com/subject/26602591/)|https://book.douban.com/subject/26602591/|
|[云计算的关键技术与应用实例](https://book.douban.com/subject/4212925/)|https://book.douban.com/subject/4212925/|
|[云计算与数据中心自动化](https://book.douban.com/subject/10803946/)|https://book.douban.com/subject/10803946/|
|[云计算 : 概念、技术与架构](https://book.douban.com/subject/26425400/)|https://book.douban.com/subject/26425400/|

##微服务

### 微服务基础
|书名|豆瓣读书链接|
|----|----|
|[微服务设计](https://book.douban.com/subject/26772677/)|https://book.douban.com/subject/26772677/|
|[微服务架构与实践（第1版）](https://book.douban.com/subject/26693152/)|https://book.douban.com/subject/26693152/|
|[Spring Cloud与Docker微服务架构实战](https://book.douban.com/subject/30278673/)|https://book.douban.com/subject/30278673/|
|[架构解密：从分布式到微服务](https://book.douban.com/subject/27081188/)|https://book.douban.com/subject/27081188/|
|[Spring Cloud微服务实战](https://book.douban.com/subject/27025912/)|https://book.douban.com/subject/27025912/|
|[Java RESTful Web Service实战](https://book.douban.com/subject/26106868/)|https://book.douban.com/subject/26106868/|


### 负载均衡
|书名|豆瓣读书链接|
|----|----|
|[深入理解Nginx（第2版） : 模块开发与架构解析](https://book.douban.com/subject/26745255/)|https://book.douban.com/subject/26745255/|
|[深入理解Nginx : 模块开发与架构解析](https://book.douban.com/subject/22793675/)|https://book.douban.com/subject/22793675/|
|[决战Nginx系统卷 : 高性能Web服务器详解与运维](https://book.douban.com/subject/10746087/)|https://book.douban.com/subject/10746087/|
|[Nginx高性能Web服务器详解](https://book.douban.com/subject/25773187/)|https://book.douban.com/subject/25773187/|


### 服务网格
|书名|豆瓣读书链接|
|----|----|
|[云原生服务网格Istio：原理、实践、架构与源码解析](https://book.douban.com/subject/34438220/)|https://book.douban.com/subject/34438220/|

## 消息队列

### kafka
|书名|豆瓣读书链接|
|----|----|
|[Apache Kafka实战](https://book.douban.com/subject/30221096/)|https://book.douban.com/subject/30221096/|
|[Apache Kafka源码剖析](https://book.douban.com/subject/27038473/)|https://book.douban.com/subject/27038473/|
|[Kafka权威指南](https://book.douban.com/subject/27665114/)|https://book.douban.com/subject/27665114/|
|[Kafka源码解析与实战](https://book.douban.com/subject/30128444/)|https://book.douban.com/subject/30128444/|
|[Kafka技术内幕](https://book.douban.com/subject/27179953/)|https://book.douban.com/subject/27179953/|
|[深入理解Kafka：核心设计与实践原理](https://book.douban.com/subject/30437872/)|https://book.douban.com/subject/30437872/|

### RabbitMQ

|书名|豆瓣读书链接|
|----|----|
|[RabbitMQ实战 : 高效部署分布式消息队列](https://book.douban.com/subject/26649178/)|https://book.douban.com/subject/26649178/|

## 数据库

### SQL
|书名|豆瓣读书链接|
|----|----|
|[精通SQL结构化查询语言详解](https://book.douban.com/subject/2022427/)|https://book.douban.com/subject/2022427/|
|[SQL学习指南（第2版）](https://book.douban.com/subject/26579980/)|https://book.douban.com/subject/26579980/|
|[SQL宝典](https://book.douban.com/subject/3691315/)|https://book.douban.com/subject/3691315/|

### MySQL
|书名|豆瓣读书链接|
|----|----|
|[MySQL必知必会](https://book.douban.com/subject/3354490/)|https://book.douban.com/subject/3354490/|
|[MySQL排错指南](https://book.douban.com/subject/26591051/)|https://book.douban.com/subject/26591051/|
|[高性能MySQL（第3版）](https://book.douban.com/subject/23008813/)|https://book.douban.com/subject/23008813/|
|[MySQL技术内幕InnoDB存储引擎（第1版）](https://book.douban.com/subject/5373022/)|https://book.douban.com/subject/5373022/|
|[MySQL技术内幕（第4版）](https://book.douban.com/subject/6524185/)|https://book.douban.com/subject/6524185/|
|[深入理解MySQL](https://book.douban.com/subject/4188364/)|https://book.douban.com/subject/4188364/|
|[MariaDB原理与实现](https://book.douban.com/subject/26340413/)|https://book.douban.com/subject/26340413/|
|[高可用MySQL（第2版）](https://book.douban.com/subject/26630834/)|https://book.douban.com/subject/26630834/|
|[MySQL内核：InnoDB存储引擎 卷1](https://book.douban.com/subject/25872763/)|https://book.douban.com/subject/25872763/|

### Oracle
|书名|豆瓣读书链接|
|----|----|
|[Oracle 10g数据库管理应用与开发标准教程](https://book.douban.com/subject/2316500/)|https://book.douban.com/subject/2316500/|
|[Oracle高效设计](https://book.douban.com/subject/1503909/)|https://book.douban.com/subject/1503909/|

### Redis
|书名|豆瓣读书链接|
|----|----|
|[Redis设计与实现](https://book.douban.com/subject/25900156/)|https://book.douban.com/subject/25900156/|

### Mongo
|书名|豆瓣读书链接|
|----|----|
|[MongoDB大数据处理权威指南（第2版）](https://book.douban.com/subject/26269829/)|https://book.douban.com/subject/26269829/|

## 大数据
### Hadoop
|书名|豆瓣读书链接|
|----|----|
|[]()||

### Spark
|书名|豆瓣读书链接|
|----|----|
|[]()||

### Flink
|书名|豆瓣读书链接|
|----|----|
|[]()||

### Hbase
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 人工智能
### 人工智能基础
|书名|豆瓣读书链接|
|----|----|
|[]()||

### TensorFlow
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 分布式
### 分布式基础
|书名|豆瓣读书链接|
|----|----|
|[]()||

### Etcd
|书名|豆瓣读书链接|
|----|----|
|[]()||

### Zookpeer
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 数据结构
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 算法
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 运维
### 运维基础
|书名|豆瓣读书链接|
|----|----|
|[]()||

### 日志
|书名|豆瓣读书链接|
|----|----|
|[]()||

### 监控告警
|书名|豆瓣读书链接|
|----|----|
|[]()||

## DevOps
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 区块链
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 性能
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 测试
### 测试基础
|书名|豆瓣读书链接|
|----|----|
|[]()||

### 性能测试
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 工具类
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 面试
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 其它资料
|书名|豆瓣读书链接|
|----|----|
|[]()||

## 按标签推荐系列 
### 微服务系列推荐
|书名|豆瓣读书链接|
|----|----|
|[]()||

### 云原生系列推荐
|书名|豆瓣读书链接|
|----|----|
|[]()||
