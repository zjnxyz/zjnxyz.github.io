
# 联系方式
（HR会打印你的简历，用于在面试的时候联系，所以联系方式放到最上边会比较方便）

- 手机：135******** （```如果是外地手机，可注明。如经常关机，要写上最优联系时间```）
- Email：goodman@gmail.com （```虽然我觉得QQ邮箱无所谓，不过有些技术人员比较反感，建议用G```）
- QQ/微信号：6*******（```提供一个通过网络可以联系到你的方式```）

---

# 个人信息

 - 胶布帝/男/1990 
 - 本科/萌鹿大学计算机系 
 - 工作年限：3年
 - 微博：[@JobDeer](http://weibo.com/jobdeer) （``` 如果没有技术相关内容，也可以不放 ```）
 - 技术博客：http://blog.github.io ( ``` 使用GitHub Host的Big较高 ```  )
 - Github: http://github.com/geekcompany ( ``` 有原创repo的Github帐号会极大的提升你的个人品牌 ```  )

 - 期望职位：Java高级程序员，架构师
 - 期望薪资：税前月薪15k~20k，特别喜欢的公司可例外
 - 期望城市：北京

---

# 工作经历

## 超级周末科技有限公司 （ 2014年4月 ~ 至今 ）
``` “超级课程表”（以下简称超表）是超级周末科技有限公司的一款面向大学生的应用，我负责 超表 和 超表管理平台 后台业务架构和开发。```
### 超级课程表
超表后台主要是由工具（课表、查成绩等）、社区（下课聊）、社交（小纸条）和电商四部分组成。我担任此项目的负责人和核心开发者，负责所有功能的架构设计和主要功能开发，同时主导的超表后台由MySQL向redis的转变，由集中式向分布式的裂变过程。
####以下是我近两年的工作
- 下课聊整体由MySQL迁移Redis,访问速度由5s上升到2s以内,并基于spring-data-redis封装了类ORM框架[开源地址](https://github.com/zjnxyz/super-redis-common)

- 随着下课聊数据的由百万级走向数亿级，出现了高峰访问越来越慢的状况。经排查，是由于单次请求redis操作过多导致的。由此提出了redis一级、二级缓存的概念。热点数据能够一次redis请求就可从一级缓存中获得。使得高峰期访问速度也能在1s以内

- 随着超表业务越来越复杂，集中式的模式越来越不利于开发和服务器的资源的利用。我带领后台部门基于dubbo和spring-boot将其分布式化。原则是新功能都是基于dubbo远程调用，旧功能按照模块依次分布式化，能够好的利用dubbo和spring-boot，也曾阅读过框架的部分源代码

- 主导后台系统按照业务进行数据库分库和读写分离，并且基于spring-data-jpa封装了一层适合公司项目的读写分离框架

- 电商平台的设计和开发。其中秒杀功能设计我认为是比较出色，宗旨是尽量将压力放在最顶层和多级的防刷方式。为止设计了多级缓存、秒杀地址动态化、验证码动态出现等机制

####基于上述工作重构后的系统架构图
![系统架构图](http://qiniu.myfriday.cn/2_1200181_7143920_1452953191289.jpg?imageView2/3/w/400)

### 推送中转服务 
推送中转服务一个公司内部所有项目消息推送的项目。


### 推送中转服务

（每个公司写2~3个核心项目就好了，如果你有非常大量的项目，那么按分类进行合并，每一类选一个典型写出来。其他的一笔带过即可。）

 
## JKL公司 （ 2010年3月 ~ 2012年8月 ）

### MNO项目 
我在此项目负责了哪些工作，分别在哪些地方做得出色/和别人不一样/成长快，这个项目中，我最困难的问题是什么，我采取了什么措施，最后结果如何。这个项目中，我最自豪的技术细节是什么，为什么，实施前和实施后的数据对比如何，同事和领导对此的反应如何。


### PQR项目 
我在此项目负责了哪些工作，分别在哪些地方做得出色/和别人不一样/成长快，这个项目中，我最困难的问题是什么，我采取了什么措施，最后结果如何。这个项目中，我最自豪的技术细节是什么，为什么，实施前和实施后的数据对比如何，同事和领导对此的反应如何。


### 其他项目

（每个公司写2~3个核心项目就好了，如果你有非常大量的项目，那么按分类进行合并，每一类选一个典型写出来。其他的一笔带过即可。）

---

# 开源项目和作品
（这一段用于放置工作以外的、可证明你的能力的材料）

## 开源项目
（对于程序员来讲，没有什么比Show me the code能有说服力了）

 - [STU](http://github.com/yourname/projectname) : 项目的简要说明，Star和Fork数多的可以注明
 - [WXYZ](http://github.com/yourname/projectname) : 项目的简要说明，Star和Fork数多的可以注明

## 技术文章
（挑选你写作或翻译的技术文章，好的文章可以从侧面证实你的表达和沟通能力，也帮助招聘方更了解你）

- [一个产品经理眼中的云计算：前生今世和未来](http://get.jobdeer.com/706.get)
- [来自HeroKu的HTTP API 设计指南(翻译文章)](http://get.jobdeer.com/343.get) （ ```好的翻译文章可以侧证你对英文技术文档的阅读能力```）

## 演讲和讲义
（放置你代表公司在一些技术会议上做过的演讲，以及你在公司分享时制作的讲义）

  - 2014架构师大会演讲：[如何通过Docker优化内部开发](http://jobdeer.com)
 - 9月公司内部分享：[云计算的前生今世](http://jobdeer.com)

# 技能清单
（我一般主张将技能清单写入到工作经历里边去。不过很难完整，所以有这么一段也不错）

以下均为我熟练使用的技能

- Web开发：PHP/Hack/Node
- Web框架：ThinkPHP/Yaf/Yii/Lavaral/LazyPHP
- 前端框架：Bootstrap/AngularJS/EmberJS/HTML5/Cocos2dJS/ionic
- 前端工具：Bower/Gulp/SaSS/LeSS/PhoneGap
- 数据库相关：MySQL/PgSQL/PDO/SQLite
- 版本管理、文档和自动化部署工具：Svn/Git/PHPDoc/Phing/Composer
- 单元测试：PHPUnit/SimpleTest/Qunit
- 云和开放平台：SAE/BAE/AWS/微博开放平台/微信应用开发

## 参考技能关键字

本技能关键字列表是从最近招聘Java的数百份JD中统计出来的，括号中是出现的词频。如果你的简历要投递给有机器（简历分选系统）和不如机器（不懂技术的HR）筛选简历环节的地方，请一定从下边高频关键词中选择5～10个适合你自己的。

- java(730)
- spring(305)
- web(260)
- mysql(250)
- oracle(207)
- linux(198)
- j2ee(182)
- javascript(177)
- sql(176)
- hibernate(169)
- html(139)
- tomcat(132)
- struts(128)
- jquery(116)
- jsp(106)
- ajax(96)
- css(94)
- ibatis(84)
- mvc(77)
- servlet(71)
- xml(70)
- js(62)
- eclipse(51)
- mybatis(51)
- jboss(47)
- struts2(47)
- weblogic(46)
- redis(46)
- apache(45)
- http(44)
- shell(39)
- python(38)
- hadoop(37)
- nosql(35)
- ssh(35)
- sqlserver(33)
- mongodb(33)
- svn(32)
- uml(32)
- json(27)
- unix(27)
- maven(27)
- nginx(26)
- webservice(25)
- jdbc(24)
- memcached(23)
- tcp(22)
- resin(22)
- jvm(21)
- socket(21)
- db2(19)
- springmvc(19)
- websphere(16)
- soa(16)
- mina(14)
- android(14)
- extjs(13)
- erp(12)
- memcache(12)
- api(11)
- jetty(11)
- myeclipse(11)
- ext(10)
- git(10)
- jpa(10)
- svm(9)
- php(9)
- jms(9)
- ruby(9)
- lucene(8)
- html5(8)
- postgresql(8)
- crm(7)
- javaee(7)
- sybase(7)
- freemarker(6)
- cache(6)
- jsf(6)
- j2se(6)
- jbpm(6)
- cvs(6)
- junit(6)
- visio(6)
- netty(6)
- hbase(6)
- nio(6)
- powerdesigner(6)
- oo(6)
- aop(6)
- workflow(5)
- restful(5)
- ios(5)
- ant(5)
- mssql(5)
- orm(5)
- rose(5)
- solr(5)
- webwork(5)
- zookeeper(4)
- soap(4)
- o2o(4)
- wap(4)
- cxf(4)
- thrift(4)
- xmpp(3)
- p2p(3)
- javabean(3)
- jee(3)
- hdfs(3)
- dom(3)
- hibernate3(3)




---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
