# audition
### 基础篇
#### 1.1 Java基础
          * 面向对象的特征：继承、封装和多态
          * final, finally, finalize 的区别
          * Exception、Error、运行时异常与一般异常有何异同
          * 请写出5种常见到的runtime exception
          * int 和 Integer 有什么区别，Integer的值缓存范围
          * 包装类，装箱和拆箱
          * String、StringBuilder、StringBuffer
          * 重载和重写的区别
          * 抽象类和接口有什么区别
          * 说说反射的用途及实现
          * 说说自定义注解的场景及实现
          * HTTP请求的GET与POST方式的区别
          * Session与Cookie区别
          * 列出自己常用的JDK包
          * MVC设计思想
          * equals与==的区别
          * hashCode和equals方法的区别与联系
          * 什么是Java序列化和反序列化，如何实现Java序列化？或者请解释Serializable 接口的作用
          * Object类中常见的方法，为什么wait  notify会放在Object里边？
          * Java的平台无关性如何体现出来的
          * JDK和JRE的区别
          * Java 8有哪些新特性
#### 1.2 Java常见集合
          * List 和 Set 区别
          * Set和hashCode以及equals方法的联系
          * List 和 Map 区别
          * Arraylist 与 LinkedList 区别
          * ArrayList 与 Vector 区别
          * HashMap 和 Hashtable 的区别
          * HashSet 和 HashMap 区别
          * HashMap 和 ConcurrentHashMap 的区别
          * HashMap 的工作原理及代码实现，什么时候用到红黑树
          * 多线程情况下HashMap死循环的问题
          * HashMap出现Hash DOS攻击的问题
          * ConcurrentHashMap 的工作原理及代码实现，如何统计所有的元素个数
          * 手写简单的HashMap
          * 看过那些Java集合类的源码
#### 1.3 进程和线程 [可参考: 《Java多线程编程核心技术》](https://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247484881&idx=2&sn=b0ecf85cd7c9e543c84e7a9859c20a26&chksm=e9c5fc60deb27576a6a9c453dabc585f43d9f29fd8a8f37ed0e7cc2f012c86b23fbd21763a39&scene=21#wechat_redirect)
          * 线程和进程的概念、并行和并发的概念
          * 创建线程的方式及实现
          * 进程间通信的方式
          * 说说 CountDownLatch、CyclicBarrier 原理和区别
          * 说说 Semaphore 原理
          * 说说 Exchanger 原理
          * ThreadLocal 原理分析，ThreadLocal为什么会出现OOM，出现的深层次原理
          * 讲讲线程池的实现原理
          * 线程池的几种实现方式
          * 线程的生命周期，状态是如何转移的
#### 1.4 锁机制 [可参考: 《Java多线程编程核心技术》](https://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247484881&idx=2&sn=b0ecf85cd7c9e543c84e7a9859c20a26&chksm=e9c5fc60deb27576a6a9c453dabc585f43d9f29fd8a8f37ed0e7cc2f012c86b23fbd21763a39&scene=21#wechat_redirect)
          * 说说线程安全问题，什么是线程安全，如何保证线程安全
          * 重入锁的概念，重入锁为什么可以防止死锁
          * 产生死锁的四个条件（互斥、请求与保持、不剥夺、循环等待）
          * 如何检查死锁（通过jConsole检查死锁）
          * volatile 实现原理（禁止指令重排、刷新内存
          * synchronized 实现原理（对象监视器
          * synchronized 与 lock 的区别
          * AQS同步队列
          * CAS无锁的概念、乐观锁和悲观锁
          * 常见的原子操作类
          * 什么是ABA问题，出现ABA问题JDK是如何解决的
          * 乐观锁的业务场景及实现方式
          * Java 8并法包下常见的并发类
          * 偏向锁、轻量级锁、重量级锁、自旋锁的概念
#### 1.5 JVM
          * JVM运行时内存区域划分
          * 内存溢出OOM和堆栈溢出SOE的示例及原因、如何排查与解决
          * 如何判断对象是否可以回收或存活
          * 常见的GC回收算法及其含义
          * 常见的JVM性能监控和故障处理工具类：jps、jstat、jmap、jinfo、jconsole等
          * JVM如何设置参数
          * JVM性能调优
          * 类加载器、双亲委派模型、一个类的生命周期、类是如何加载到JVM中的
          * 类加载的过程：加载、验证、准备、解析、初始化
          * 强引用、软引用、弱引用、虚引用
          * Java内存模型JMM
#### 1.6 设计模式
          * 常见的设计模式
          * 设计模式的的六大原则及其含义
          * 常见的单例模式以及各种实现方式的优缺点，哪一种最好，手写常见的单利模式
          * 设计模式在实际场景中的应用
          * Spring中用到了哪些设计模式
          * MyBatis中用到了哪些设计模式
          * 你项目中有使用哪些设计模式
          * 说说常用开源框架中设计模式使用分析
          * 动态代理很重要！！！
#### 1.7 数据结构
          * 树（二叉查找树、平衡二叉树、红黑树、B树、B+树）
          * 深度有限算法、广度优先算法
          * 克鲁斯卡尔算法、普林母算法、迪克拉斯算法
          * 什么是一致性Hash及其原理、Hash环问题
          * 常见的排序算法和查找算法：快排、折半查找、堆排序等
#### 1.8 网络/IO基础  [从输入URL到页面加载发生了什么](https://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483724&idx=1&sn=e58dd30d124971c795584e8673d6cc71&chksm=e9c5f8fddeb271ebebbb6c350ed1abc252f1f26b4f35c4ce36e10bde9659a37520feabed2290&scene=21#wechat_redirect)
          * BIO、NIO、AIO的概念
          * 什么是长连接和短连接
          * Http1.0和2.0相比有什么区别
          * Https的基本概念
          * 三次握手和四次挥手、为什么挥手需要四次
          * 从游览器中输入URL到页面加载的发生了什么？
### 数据存储和消息队列
#### 2.1 数据库
          * MySQL 索引使用的注意事项
          * DDL、DML、DCL分别指什么
          * explain命令
          * left join，right join，inner join
          * 数据库事物ACID（原子性、一致性、隔离性、持久性）
          * 事物的隔离级别（读未提交、读以提交、可重复读、可序列化读）
          * 脏读、幻读、不可重复读
          * 数据库的几大范式
          * 数据库常见的命令
          * 说说分库与分表设计
          * 分库与分表带来的分布式困境与应对之策（如何解决分布式下的分库分表，全局表？）
          * 说说 SQL 优化之道
          * MySQL遇到的死锁问题、如何排查与解决
          * 存储引擎的 InnoDB与MyISAM区别，优缺点，使用场景
          * 索引类别（B+树索引、全文索引、哈希索引）、索引的原理
          * 什么是自适应哈希索引（AHI）
          * 为什么要用 B+tree作为MySQL索引的数据结构
          * 聚集索引与非聚集索引的区别
          * 遇到过索引失效的情况没，什么时候可能会出现，如何解决
          * limit 20000 加载很慢怎么解决
          * 如何选择合适的分布式主键方案
          * 选择合适的数据存储方案
          * 常见的几种分布式ID的设计方案
          * 常见的数据库优化方案，在你的项目中数据库如何进行优化的
### 2.2 Redis
          * Redis 有哪些数据类型
          * Redis 内部结构
          * Redis 使用场景
          * Redis 持久化机制
          * Redis 集群方案与实现
          * Redis 为什么是单线程的？
          * 缓存雪崩、缓存穿透、缓存预热、缓存更新、缓存降级
          * 使用缓存的合理性问题
          * Redis常见的回收策略
### 2.3 消息队列
          * 消息队列的使用场景
          * 消息的重发补偿解决思路
          * 消息的幂等性解决思路
          * 消息的堆积解决思路
          * 自己如何实现消息队列
          * 如何保证消息的有序性
### 开源框架和容器
#### 3.1 SSM/Servlet
          * Servlet的生命周期
          * 转发与重定向的区别
          * BeanFactory 和 ApplicationContext 有什么区别
          * Spring Bean 的生命周期
          * Spring IOC 如何实现
          * Spring中Bean的作用域，默认的是哪一个
          * 说说 Spring AOP、Spring AOP 实现原理
          * 动态代理（CGLib 与 JDK）、优缺点、性能对比、如何选择
          * Spring 事务实现方式、事务的传播机制、默认的事务类别
          * Spring 事务底层原理
          * Spring事务失效（事务嵌套），JDK动态代理给Spring事务埋下的坑
          * 如何自定义注解实现功能
          * Spring MVC 运行流程
          * Spring MVC 启动流程
          * Spring 的单例实现原理
          * Spring 框架中用到了哪些设计模式
          * Spring 其他产品（Srping Boot、Spring Cloud、Spring Secuirity、Spring Data、Spring AMQP 等）
          * 有没有用到Spring Boot，Spring Boot的认识、原理
          * MyBatis的原理
#### 3.2 Netty
          * 为什么选择 Netty
          * 说说业务中，Netty 的使用场景
          * 原生的 NIO 在 JDK 1.7 版本存在 epoll bug
          * 什么是TCP 粘包/拆包
          * TCP粘包/拆包的解决办法
          * Netty 线程模型
          * 说说 Netty 的零拷贝
          * Netty 内部执行流程
          * Netty 重连实现
#### 3.3 Tomcat[可参考：《四张图带你了解Tomcat系统架构！》](https://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247484905&idx=1&sn=6c8acd89476fadbc4cb9ccfda9c9c2e4&chksm=e9c5fc58deb2754e7519511bb0ed8dcbfa3fe29179663b53f3626643f8b9c82068d9b0464ee6&scene=21#wechat_redirect)
          * Tomcat的基础架构（Server、Service、Connector、Container）
          * Tomcat如何加载Servlet的
          * Pipeline-Valve机制
### 分布式
#### 4.1 Nginx
          * 请解释什么是C10K问题或者知道什么是C10K问题吗？
          * Nginx简介，可参考《Nginx简介》
          * 正向代理和反向代理
          * Nginx几种常见的负载均衡策略
          * Nginx服务器上的Master和Worker进程分别是什么
          * 使用“反向代理服务器”的优点是什么?
#### 4.2 分布式其他[可参考《数据库分库分表策略的具体实现方案》](https://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483931&idx=1&sn=6eda41aa81c1243422a603205d2fad22&chksm=e9c5fbaadeb272bc92537803c14a6f55e1170b1a3b8f60160f66417800c0ace960dfe192717a&scene=21#wechat_redirect)
          * 谈谈业务中使用分布式的场景
          * Session 分布式方案
          * Session 分布式处理
          * 分布式锁的应用场景、分布式锁的产生原因、基本概念
          * 分布是锁的常见解决方案
          * 分布式事务的常见解决方案
          * 集群与负载均衡的算法与实现
          * 说说分库与分表设计
          * 分库与分表带来的分布式困境与应对之策
#### 4.3 Dubbo[可参考《基于HTTP的RPC实现》](https://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247483900&idx=1&sn=c5ca198a66a701f81c2ab118fe7a734a&chksm=e9c5f84ddeb2715bc574e467cd6537ef81f223453e0989ffd136976b48dcc2d961a75be596de&scene=21#wechat_redirect)
          * 什么是Dubbo
          * 什么是RPC、如何实现RPC、RPC 的实现原理
          * Dubbo中的SPI是什么概念
          * Dubbo的基本原理、执行流程
### 微服务
#### 5.1 微服
     * 前后端分离是如何做的？
     * 微服务哪些框架
     * Spring Could的常见组件有哪些？可参考《Spring Cloud概述》
     * 领域驱动有了解吗？什么是领域驱动模型？充血模型、贫血模型
     * JWT有了解吗，什么是JWT，可参考《前后端分离利器之JWT》
     * 你怎么理解 RESTful
     * 说说如何设计一个良好的 API
     * 如何理解 RESTful API 的幂等性
     * 如何保证接口的幂等性
     * 说说 CAP 定理、BASE 理论
     * 怎么考虑数据一致性问题
     * 说说最终一致性的实现方案
     * 微服务的优缺点，可参考《微服务批判》
     * 微服务与 SOA 的区别
     * 如何拆分服务、水平分割、垂直分割
     * 如何应对微服务的链式调用异常
     * 如何快速追踪与定位问题
     * 如何保证微服务的安全、认证
#### 5.2 安全问题
     * 如何防范常见的Web攻击、如何方式SQL注入
     * 服务端通信安全攻防
     * HTTPS原理剖析、降级攻击、HTTP与HTTPS的对比
#### 5.3 性能优化
     * 性能指标有哪些
     * 如何发现性能瓶颈
     * 性能调优的常见手段
     * 说说你在项目中如何进行性能调优
### 其他
#### 6.1 设计能力
     * 说说你在项目中使用过的UML图
     * 你如何考虑组件化、服务化、系统拆分
     * 秒杀场景如何设计
     * 可参考：《秒杀系统的技术挑战、应对策略以及架构设计总结一二！》
#### 6.2 业务工程
     * 说说你的开发流程、如何进行自动化部署的
     * 你和团队是如何沟通的
     * 你如何进行代码评审
     * 说说你对技术与业务的理解
     * 说说你在项目中遇到感觉最难Bug，是如何解决的
     * 介绍一下工作中的一个你认为最有价值的项目，以及在这个过程中的角色、解决的问题、你觉得你们项目还有哪些不足的地方
#### 6.3 软实力
     * 说说你的优缺点、亮点
     * 说说你最近在看什么书、什么博客、在研究什么新技术、再看那些开源项目的源代码
     * 说说你觉得最有意义的技术书籍
     * 工作之余做什么事情、平时是如何学习的，怎样提升自己的能力
     * 说说个人发展方向方面的思考
     * 说说你认为的服务端开发工程师应该具备哪些能力
     * 说说你认为的架构师是什么样的，架构师主要做什么
     * 如何看待加班的问题
