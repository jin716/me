
## 个人信息

* 李景/男/1984 
* 硕士/中山大学 软件工程 
* 工作年限：13年
* Github：[http://jin716.github.io/](http://jin716.github.io/me)
* 所在城市：珠海
* 意向城市：珠海

#### 联系方式

* 手机/微信号：18688862168 
* Email：doug.lea@foxmail.com

#### 现任职务及头衔
* 远光信创平台基础服务组架构师 
* 远光信创平台AI中心组开发经理
* 远光信创平台技术管控组成员
* 北京理工大学珠海学院校企合作指导导师
* 远光星火计划高校讲师
* 国家专利发明人

## 技能清单

###### 主要技能

* 从事多年Java开发，设计，架构，微服务架构，底层框架研发以及性能调优的工作，特别擅长底层性能分析优化，微服务架构设计开发等。
* 制定公司平台级开发规范，指导评审管控开发过程。
* 良好的编码风格,命名规范。

###### 使用过的技术

* Web开发：PHP/JQuery/Boostrap
* 数据库相关：Oracle/MySQL/SQLite/Redis
* 分布式: Hadoop/Docker
* 服务器：Tomcat/Nginx
* 版本管理、文档和自动化部署工具：Svn/Git/Maven
* 单元测试：JUnit
* 开放平台：AWS/微博开放平台/微信应用开发
* IDE:MyEclipse/Intellij/VIM/Sublime/PyCharm
* 序列化：Protobuf/XML/Json
* 消息中间件：IBM MQ
* 脚本：Python/Shell
* 英语:CET-6/口语流利

###### 专利技术
* 《一种日志系统的调控方法、装置、存储介质及电子设备》
* 《一种基于网络隔离的可适配网关的数据处理方法》

## 工作经历
#### 2017年4月-至今 远光软件信创平台部 基础服务组架构师 AI中心组开发经理
  
###### 主要项目经历

###### 远光低代码开发平台 远光九天智能语言研发 2021年10月-至今

&emsp;&emsp;远光九天智能语言，是公司为实现低代码开发的战略性研发方向。其目的一个是降低对国外开源软件的依赖，另一个是结合自身情况进行代码开发的探索。
我负责的工作包括：  
1. YJDL远光九天模型语言的开发设计：  
2. YJDL数据库访问语言，一套基于原生Java开发的基于模型的数据库访问API，整合远光九天的模型设计能力进行数据库增删改查操作，其原理与ORMapping类似，但更进一步变成Object-Model-Mapping：模型与对象的映射。通过模型对象映射，达到了设计即实现的目的，统一了数据库模型设计阶段与代码开发实现，从而更好的沉淀模型，复用模型。  
3. 模型SQL解析引擎，通过Druid Sqlparser 开源工具 结合基于调用栈的递归算法对SQL的表名，列名进行解析替换，实现模型定义与具体SQL规范的转换，最终实现一次SQL编写，到处运行的目的，极大简化了开发团队的开发效率。  


###### 国家电网财务管控应用分离架构转型 2019年6月-2020年4月

&emsp;&emsp;作为核心人员全程参与，将公司原有软件系统架构从传统单体架构转型微服务化，主要包括以下几个过程：
1. 软件开发的规范化和平台化，提供和制定平台化开发工具和开发标准。
2. 开发设计系统底层拆分的服务路由策略，将系统所有的动静态资源，REST接口等调用进行梳理，最终按业务能力拆分出30个微应用。
3. 其中涉及到：基于数据库的服务注册，原生的网络请求转发，定制化的RMI工具，安全校验机制，数据的序列化与反序列化，链路跟踪与异常定位等功能的开发应用。
4. 指导并配合这30个微应用开发团队进行应用分离开发， 以及后续阶段的微服务化迁移，最终彻底实现微服务化。

成功将运行十年的国家电网财务管理系统进行了应用分离并上线，为公司在微服务转型时期做出核心贡献。
获得公司年度技术突破奖

###### 基于数据库的内外网HTTP交互网关 2020年3月

&emsp;&emsp;因为特殊安全限制, 外网只能通过一套特殊的JDBC访问机制, 通过数据库进行与内网进行数据交互,无法满足业务http访问穿透内外网的需求, 因此提出基于数据库的http网关.
通过封装filter层拦截http请求,对请求和响应进行序列化反序列化,在数据库层进行交互, 响应返回并恢复挂起的线程, 达到了虚拟网关的目的, 支持高并发并稳定运行.

主要原理提取成专利材料，以第一作者的身份发表：《一种基于网络隔离的可适配网关的数据处理方法》


###### 日志写入性能优化 2018年1月

&emsp;&emsp;针对log4j.1.2.15日志在高并发的情况下，造成阻塞，在内部压测环节被发现。
通过Jstack收集运行数据，定位到阻塞点，并展开对源代码的分析调查，发现其因为设计不合理导致线程在高并发的情况下竞争文件写锁导致不必要的性能损耗， 最终修改源代码，通过消除锁竞争及弹性队列的机制极大优化了写入性能。

实测写入性能提升2倍。  
主要原理提取成专利材料，以第一作者的身份发表：《一种日志系统的调控方法、装置、存储介质及电子设备》 


###### 远光电价大数据运算项目 2018年4月

&emsp;&emsp;该项目是早期公司实践创新的重点项目，在开发的过程中被要求同时使用3种技术栈进行计算比较：数据库sql计算，Java原生计算，Hadoop大数据计算。我负责Java原生计算，和与Spark核心计算引擎的开发。
最终的方案是spark作为计算引擎，hdfs作为文件数据存储，通过定时调度任务将计算数据导入hdfs中并触发计算.

最终达到了1.4亿数据在20分钟内计算完成的目标，实测12分钟。
先后在山西省国家电网等多个地方落地，为电价实时计算，实现用电资源的市场动态调节，为国家节能减排做出了贡献。

###### 天擎注册中心

&emsp;&emsp;我负责3个阶段的注册中心的接入开发  
1. 原生初始时期: 此时是应用分离微服务的初始阶段,没有依赖外部注册中心, 基于内部数据库实现的服务注册版本. 通过filter层及调用工具实现的调用转发,共包括4大类型的注册:
静态资源,接口资源,类资源,模型资源的注册及转发关系, 使用基本的随机负载均衡.  
2. 引入注册中心早期: 此时引入了Eureka注册中心, 通过定义一般注册接口制定注册中心API接入的基础. 封装Eureka注册中心接口以及开发,并引入基于响应实践的负载均衡算法。   
3. 成熟期： 注册中心功能接口丰富完善, 引入nacos, tsf等多种注册中心，功能更加强大。这一阶段我主要负责代码审核及设计。      

三个时期的发展与远光微服务化从无到有到成熟一同发展。  

###### 天擎搜索服务



###### 其他项目汇总


###### 远光星火计划高校金牌讲师计划 企业指导教师
&emsp;&emsp;在北京理工大学珠海学院，北京师范大学珠海分校，广东财经大学， 江西财经大学等周边多个院校进行合作，教授微服务开发基础及生产开发实践。  
&emsp;&emsp;京理工大学珠海学院签约毕业生辅导教师，指导毕业设计等工作。


#### 2015年8月-2017年4月 工行珠海研发中心 CCF平台研发工程师（编制外）

###### 相关项目
###### 工银国际清算结算业务
 * 我所在团队核心业务，简单概况就是银行资金报文的处理与转发，为确保各种不同格式的报文能够正确流转，通过Tomcat服务器对外暴露的报文接受接口，接受来自与MQ,网关等不同渠道的报文，通过报文解析程序将报文转到不同的工作流中，再根据业务需要进行报文流转。
 * 所在期间成功上线的开发任务包括：马德里，加拿大，纽约，莫斯科，泰国分行10月个版本的开发，负责时时0生产问题。

###### 工银CCF敏捷监控平台
	
* 敏捷监控是一个基于国内外清算业务的性能指标监控平台，通过提取数据库、JVM运行数据、日志信息等特征数据，对工行海内外清算业务进行全方位的监控。每日监控业务信息十万笔以上。  
* 我的工作：基于Hadoop的日志分析系统，通过编写MapReduce程序，提取特定特征的业务信息，和异常信息，汇总到业务监控平台。在业务日志，异常日志的提取和查询上极大的提升了同事的开发分析效率。

###### 工银支付团队PSCP核心平台服务化重构  
 
 * 该服务化重构重点包括：平台化服务由MVC业务模型，转为面向服务的服务模型。
 * 我的工作：将紧密耦合到数据库的PL/SQL的业务程序，解耦到基于MyBatis的服务框架中。

  
#### 2014年3月-2015年8月  [COME](http://mindate.cn) 后台开发工程师/创始人
COME是一个基于兴趣，LBS的小清新交友APP。COME后台基于HTTPS协议，通过JSON传输数据对Andoid、iOS客户端进行支撑。后台由外包公司和我共同开发维护.  
技术工具: JFinal/Jedis/Redis/MyBatis/Mysql/Hadoop/Netty/Protobuf  
我的工作:    
* 根据标签，时间，坐标三个因素对用户进行智能排序。对寻找附近的人，**引入基于坐标的二分法算法**，对经纬度进行哈希，用哈希值索引替代SQL坐标数值查询判定，立竿见影的提升了性能瓶颈。 
* 聊天后台序列化方式改造，对原外包公司提供的XMPP聊天协议进行改造，使用Netty+Protobuf自定义协议栈开发聊天后台，对比原方案减少80%以上的的服务带宽，有效节省客服两端的聊天流量。  
* 使用Bootstarp+JQuery快速开发的web管理页面。
* 兼任项目经理，组建并稳定初始技术团队，在任期间无人离职，并顺利完成预定版本目标。
  

#### 2010年-2014年3月 拓见集团 技术部经理
技术工具：Struts/Hibernate/JQuery/PHP/Wechat API

* 组建技术部门，策划团队架构，招募新人，发起基本的JAVA技术培训等。
* 基于SSH的ERP系统二次开发。
* 企业微信公众号API调用开发。
* ECShop PHP商城改造开发。
* 电话外呼客服业务应用系统开发，实施培训与管理。

#### 2009年-2010年 中国联通总部wo手机邮箱事业部 技术支持

## 其他项目
#### 饭快快网 （2010年） 
饭快快网是我和朋友两个人写的，2010年期间曾经是广州百度排第一的外卖网站.  
Github：[https://github.com/jin716/fankk](https://github.com/jin716/fankk)  
我的工作：

* 爬取百度地图API，获取全广州外卖信息，使得网站内容得到极大丰富，配合URL参数静态化等手段，网站百度自然排名升到“广州外卖”第一的位置。
* 通过开发短信订单通知、短信订单打印功能，解决了门面无电脑的外卖商家加盟问题。
* 整个外卖网站的开发部署。

#### 国家无线电第五研究所技术文档批量生成工具
#### 研究生阶段项目：遗传算法求解最短路径时的应用与实现
#### 研究生阶段项目：基于KNN算法的验证码识别

##  开源项目

#### [ZhihuTag](https://github.com/jin716/zhihuTag) （原创）
根据话题关键字，搜索对此关键字最擅长的人，并根据这些用户在该话题下的赞数进行排序。  

技术工具：Python/BeautifulSoup/Redis/Mysql/RestAPI   
技术实现：通过Redis中央队列的形式，对知乎的标签页进行广度优先遍历，通过FIFO，实现分布式爬虫,并协同抓取全知乎的标签及子标签的树状结构，将此全量树状结构存储入数据库。此机制保证任何一个爬虫技能单独而协同。



## 兴趣爱好
#### 马拉松及铁人三项
深圳最早的越野跑团-[扬眉堂](http://www.weibo.com/u/5385509748)的创始人之一。  
特长是运动伤病预防与恢复，对人体动作模式，慢性劳损，肌肉康复，MAF训练有一定研究。

#### 个人成绩：  
* 2019年广州从化100 50公里组男子16名
* 香港LanTau50公里越野跑 成绩：12小时
