
## 个人信息

* 李景/男/1984 
* 硕士/中山大学 软件工程 
* 工作年限：11年
* Github：[http://jin716.github.io/](http://jin716.github.io/me)
* 所在城市：珠海
* 意向城市：珠海/广州/深圳

#### 联系方式

* 手机/微信号：18688862168 
* Email：doug.lea@foxmail.com

## 技能清单

###### 主要技能

* 从事多年微服务架构，底层框架研发以及性能调优，擅长底层性能分析优化等.
* Java，MVC模型，面向服务模型，有多年开发经验。
* 编写RestAPI经验，并能针对小型应用迅速开发分布式API。
* 熟练使用链表，堆，MAP、二叉树、B+树，红黑树等数据结构，并能运用在实际工作中。
* 对多线程有深入理解，对concurrent包，collection包源码有深入理解，并熟练使用。
* 深入理解JVM运行机制及内存模型，有JVM参数调优经验, 有针对heapdump进行分析优化的经验。
* 熟练使用BTrace对线上JVM进行性能分析，根据回馈做性能调优，并理解其原理。
* 熟悉TCP/IP协议，熟悉HTTP协议，IO/NIO原理，熟悉网络编程，对Netty及其核心代码有深入研究。
* 使用过的框架有:netty,ibatis,hibernate,spring，springBoot,jfinal,struct
* 善于运用设计模式做整洁设计，消除重复代码。
* 有使用Junit 做单元测试的习惯。
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

## 工作经历
#### 2017年4月-至今 远光软件 ECP设计部架构师 AI中心开发经理
  
###### 相关项目
###### 应用分离架构转型项目 核心架构设计及开发
主导公司整个OSGI项目从传统ERP单体架构转转型微服务化改造，通过服务路由策略，将公司所有的动静态资源，REST接口等调用进行梳理和拆分，同时支撑30个下级开发团队进行微服务化改造。
成功将运行十数年的国家电网财务管理ERP系统进行了应用分离并上线，为公司微服务转型做出核心贡献。

###### PAAS平台研发
涉及领域日志，搜索，调度，负载均衡，微服务注册中心，数据库访问层开发设计等工作， 涉及底层研发与性能优化等， 在该领域多次完成技术攻关，技术普及指导，获得公司技术进步奖项荣誉及国家专利等。

###### 远光星火计划高校金牌讲师计划 企业指导教师
在省周边多个院校进行合作，教授微服务开发基础。
北理工签约毕业生辅导教师，指导毕业设计等工作。


#### 2015年8月-2017年4月 信雅达金融研发部 研发工程师

   此间作为核心成员完满完成多个分行及项目组的开发，由于技术于工作能力获得认可，先后受工行珠海，杭州研发部门邀请加入，但由于银行技术方向与个人期望有差距，因此婉拒了较为稳定的环境并打算离开，寻由求量变到质变的自我突破机会。 
  
###### 相关项目
###### 工银国际清算结算业务
 * 我所在团队核心业务，简单概况就是银行资金报文的处理与转发，为确保各种不同格式的报文能够正确流转，通过Tomcat服务器对外暴露的报文接受接口，接受来自与MQ,网关等不同渠道的报文，通过报文解析程序将报文转到不同的工作流中，再根据业务需要进行报文流转。
 * 所在期间成功上线的开发任务包括：马德里，加拿大，纽约，莫斯科，泰国分行10月个版本的开发，至今0生产问题。

###### 工银CCF敏捷监控平台
	
* 敏捷监控是一个基于国内外清算业务的性能指标监控平台，通过提取数据库、JVM运行数据、日志信息等特征数据，对工行海内外清算业务进行全方位的监控。每日监控业务信息十万笔以上。  
* 我的工作：基于Hadoop的日志分析系统，通过编写MapReduce程序，提取特定特征的业务信息，和异常信息，汇总到业务监控平台。在业务日志，异常日志的提取和查询上极大的提升了同事的开发分析效率。

###### 工银支付团队PSCP核心平台服务化重构  
 
 * 该服务化重构重点包括：平台化服务由MVC业务模型，转为面向服务的服务模型。
 * 我的工作：将紧密耦合到数据库的PL/SQL的业务程序，解耦到基于MyBatis的服务框架中。

  
#### 2014年3月-2015年8月  [COME](http://mindate.cn) 后台开发工程师/前任法人
COME是一个基于兴趣，LBS的小清新交友APP。COME后台基于HTTPS协议，通过JSON传输数据对Andoid、iOS客户端进行支撑。后台由外包公司和我共同开发维护.  
技术工具: JFinal/Jedis/Redis/MyBatis/Mysql/Hadoop/Netty/Protobuf  
我的工作:  

* 根据标签，时间，坐标三个因素对用户进行智能排序。对寻找附近的人，**引入基于坐标的二分法算法**，对经纬度进行哈希，用哈希值索引替代SQL坐标数值查询判定，立竿见影的提升了性能瓶颈。 
* 聊天后台序列化方式改造，对原外包公司提供的XMPP聊天协议进行改造，使用Netty+Protobuf自定义协议栈开发聊天后台，对比原方案减少80%以上的的服务带宽，有效节省客服两端的聊天流量。  
* 使用Bootstarp+JQuery快速开发的web管理页面。
* 兼任项目经理，组建并稳定初始技术团队，在任期间无人离职，并顺利完成预定版本目标。
  

#### 2010年-2014年3月 拓见集团 技术部经理
技术工具：Struts/Hibernate/JQuery/PHP/Wechat API

* 组建技术部门，策划团队架构，招募新人，发起基本的JAVA技术培训等。
* 基于SSH的ERP系统二次开发。
* 企业微信公众号API调用开发。
* ECShop PHP商城改造开发。
* 电话外呼客服业务应用系统开发，实施培训与管理。

#### 2009年-2010年 中国联通总部wo手机邮箱事业部 技术支持

## 其他项目
#### 饭快快网 （2010年） 
饭快快网是我和另一个搭档两个人写的，2010年期间曾经是广州百度排第一的外卖网站.  
Github：[https://github.com/jin716/fankk](https://github.com/jin716/fankk)  
我的工作：

* 爬取百度地图API，获取全广州外卖信息，使得网站内容得到极大丰富，配合URL参数静态化等手段，网站百度自然排名升到“广州外卖”第一的位置。
* 通过开发短信订单通知、短信订单打印功能，解决了门面无电脑的外卖商家加盟问题。
* 整个外卖网站的开发部署。

#### 国家无线电第五研究所技术文档批量生成工具
* 基于B/S架构的，通过模版形式的word文档生成工具。
#### 研究生阶段项目：遗传算法求解最短路径时的应用与实现
#### 研究生阶段项目：基于KNN算法的验证码识别

##  专利技术
国家专利 一种非阻塞日志IO技术
国家专利 基于内外网交互的


##  开源项目

#### [ZhihuTag](https://github.com/jin716/zhihuTag) （原创Repo,建设中）
根据话题关键字，搜索对此关键字最擅长的人，并根据这些用户在该话题下的赞数进行排序。  

技术工具：Python/BeautifulSoup/Redis/Mysql/RestAPI   
技术实现：通过Redis中央队列的形式，对知乎的标签页进行广度优先遍历，通过FIFO，实现分布式爬虫,并协同抓取全知乎的标签及子标签的树状结构，将此全量树状结构存储入数据库。此机制保证任何一个爬虫技能单独而协同。



## 爱好
#### 马拉松
深圳最早的越野跑团-[扬眉堂](http://www.weibo.com/u/5385509748)的创始人之一。  
特长是运动伤病预防与恢复，对人体动作模式，慢性劳损，肌肉康复，MAF训练有一定研究。长跑让我拥有比同龄人更健康的身体，长时间工作保持精力充沛，头脑清醒。
#### 个人成绩：  
* 香港LanTau50公里越野跑 成绩：12小时

#### 模拟赛车
#### DIY赛车G力座椅
通过读取模拟赛车游戏中的游戏数据， 将数据通过串口传输到STM32芯片，编写代码产生相应的脉冲信号，控制两台伺服电机控制座椅的动态，达到动态仿真座椅的效果。
#### DIY赛车感应式风扇
通过读取模拟赛车游戏中的速度数据，用stm32芯片控制风扇转速，使得赛车在高速运行中有风吹脸的敞篷效果。
