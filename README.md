# 联系方式

- 手机：18102215296
- Email：zjn_2012@foxmail.com
- 微信号：zjn_xyz

----

# 个人信息

 - 朱江楠/男/1990 
 - 本科/九江学院
 - 工作年限：3年
 - 技术博客：[http://my.oschina.net/u/241255](http://my.oschina.net/u/241255)
 - Github: [https://github.com/zjnxyz](https://github.com/zjnxyz)
 - 资格水平：系统架构师（高级）
 - 期望职位：java高级工程师，应用架构师
 - 期望薪资：税前月薪18k~20k

---

# 工作经历
## 超级周末科技有限公司 （ 2014年4月 ~ 至今 ）
``` “超级课程表”（以下简称超表）是超级周末科技有限公司的一款面向大学生的应用，我负责 超表 和 超表管理平台 后台业务架构和开发。```
### 超级课程表
超表后台主要是由工具（课表、查成绩等）、社区（下课聊）、社交（小纸条）和电商四部分组成。我担任此项目的负责人和核心开发者，负责所有功能的架构设计和主要功能开发，同时主导的超表后台由MySQL向redis的转变，由集中式向分布式的裂变过程。
####以下是我近两年的工作
- 下课聊整体由MySQL迁移Redis,访问速度由5s上升到3s以内,并基于spring-data-redis封装了类ORM框架[【开源地址】](https://github.com/zjnxyz/super-redis-common)

- 随着下课聊数据的由百万级走向数亿级，出现了高峰访问越来越慢的状况。经排查，是由于单次请求redis操作过多导致的。由此提出了redis一级、二级缓存的概念。热点数据能够一次redis请求就可从一级缓存中获得。使得高峰期访问速度也能在2s以内

- 随着超表业务越来越复杂，集中式的模式越来越不利于开发和服务器的资源的利用。我带领后台部门基于dubbo和spring-boot将其分布式化。原则是新功能都是基于dubbo远程调用，旧功能按照模块依次分布式化，能够好的利用dubbo和spring-boot，也曾阅读过框架的部分源代码

- 主导后台系统按照业务进行数据库分库和读写分离，并且基于spring-data-jpa封装了一层适合公司项目的读写分离框架

- 电商平台的设计和开发。其中秒杀功能设计我认为是比较出色，宗旨是尽量将压力放在最前端和多种动态防刷策略。为止设计了多级缓存、秒杀地址动态化、验证码动态出现等机制

####基于上述工作重构后的系统架构图
![系统架构图](http://qiniu.myfriday.cn/2_1200181_7143920_1452953191289.jpg?imageView2/3/w/400)

### 推送中转服务 
推送中转是为公司所有系统提供消息推送服务的项目。目前每天的消息中转推送量大概在千万级别。中转服务是基于scala和akka实现的分布式的系统，包含master(管理者，负责管理client和worker的状态)、client(集成到需要推送的系统中)和worker(消息中转推送的实际工作者)。各组件之间都是通过akka自定义协议进行通信。
####基于akka的推送服务系统架构图
![系统架构图](http://qiniu.myfriday.cn/2_1200181_7143920_1452955409884.jpg?imageView2/3/w/400)

### 超表内部管理平台
该项目是由我于2015年9月发起，目的是为了整合公司各自为政的大大小小的管理系统。基于spring-security设计了符合公司目前业务的权限管理平台，为各个业务提供了基于角色的细粒度的权限控制，保证了系统的安全性。目前，公司大多数系统都已迁移到这个平台。
 
## 中科软科技股份有限公司（ 2013年4月 ~ 2014年3月 ）

``中科软科技股份有限公司（以下简称中科软）是专门从事计算机软件研发、应用、服务的智能密集型高新技术企业，入职公司众诚项目组，担任java开发工程师，从事与保险业务相关的系统开发。``

### 众诚车险理赔系统
主要负责理赔系统的日常维护和新功能的开发。曾负责理赔浙分平台的开发，经历过理赔的报案、查勘到理算的整个过程。理赔系统的难点在于整个流程过于漫长，存在很多的细节问题。

### 众诚车险微信公众平台
负责整个项目的功能开发，使用java对微信公众平台的api进行了二次封装。系统中需要用到理赔和承保系统的业务数据，经过对比，采用了基于cxf的webservice进行系统间的调用。为了使代码更加的优雅和具有更好的可扩展性，系统使用了一些设计模式，例如责任链模式、状态模式、策略模式等。

---

# 开源项目
 - [spuer-redis-common](https://github.com/zjnxyz/super-redis-common) :采用ORM的方式封装对redis操作，同时也基于redis实现了简单的消息队列模板方法。目前该项目运用公司十来个项目中。
 - [super-auto-code](https://github.com/zjnxyz/super-redis-common):代码生成工具，采用yam配置形式，可生成model，dao，service的模板方法，支持redis、读写分离等配置。

# 技能清单
（我一般主张将技能清单写入到工作经历里边去。不过很难完整，所以有这么一段也不错）

以下均为我熟练使用的技能

- Web开发：java/scala/ruby
- Web框架：Spring相关框架（Spring-boot，Spring-data,spring-security等）
- 数据库相关：MySQL/Redis/MongoDB
- 版本管理、文档和自动化部署工具：Svn/Git
- 单元测试：Junit

# 2015年读书清单

# 证书与奖励
- 2010年—2012年分别通过全国计算机技术与软件专业资格（水平）考试的系统架构设计师（高级）、软件设计师（中级）、数据库系统工程师（中级）
- 2013年6月 撰写的《基于Mahout的个性化推荐在作业管理系统上的设计与实现》获得校级优秀毕业论文称号
- 2010年—2013年分别获得一次国家励志奖学金，两次校级二等奖学金，三次校级三等奖学金
- 2013年5月 撰写的论文《基于协同过滤推荐技术的作业资源个性化推荐系统设计与研究》 发表在《电子世界》杂志上，用稿编号rj-dz-2013-05-035

# 教育经历
2009年9月 – 2013年6月    九江学院    信息管理与信息系统专业
---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
