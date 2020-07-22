# Java-knowledge


## Spring
 - IOC：[Spring中IOC知识点介绍](https://mp.weixin.qq.com/s?__biz=MzI5NTk0MDkwNA==&mid=2247483703&idx=1&sn=c409488c95870d367162923075fed2cc&chksm=ec4aa770db3d2e6652c0c77cdf26a37dc6ea2a2486020ab9b632ec82f4bc0fa2c40290ffa396&scene=126&sessionid=1595328353&key=de438a290b06e75a5e8ee474df644893b6e0dcb29e2b34dc49617ea5d5adcbbf6af01f91a947036fe9805bb6b1ffb1a8d31982f7bc4f6f404231a20db9d0d29bb8aa2114159a01452bba955d137607cf&ascene=1&uin=MzU1MjE3NTAy&devicetype=Windows+10+x64&version=62090529&lang=zh_CN&exportkey=AeOFXcRKpXW5Blt9JlAJT2s%3D&pass_ticket=%2FJDJX3%2FxUFIRv8nz2s3qp6eYjByCRxZIquJcbqP%2Bv1Qq3X92dpF8p6Rl6QM1QGL4)
 - AOP：[Spring中AOP知识点介绍](https://mp.weixin.qq.com/s?__biz=MzI5NTk0MDkwNA==&mid=2247483666&idx=1&sn=488079b58f2387ee45b18f451eddb648&chksm=ec4aa755db3d2e43531e9a2ba4cc0ce64344c7bf9843dcea1613694db2fdaee4358b36f16b9c&token=200295296&lang=zh_CN#rd)
 </details>
 
## 集合：[Java集合分析](https://blog.csdn.net/qq_40126996/article/details/106063070)
 - Collection
   - List
     - ArrayList
     - LinkedList
     - Vector
   - Set
     - HashSet
     - TreeSet
  - Map
    - TreeMap
    - HashTable
    - HashMap：[从源码分析HashMap](https://mp.weixin.qq.com/s?__biz=MzI5NTk0MDkwNA==&mid=2247483654&idx=1&sn=81f376bd85b103bf2493782ba08ce142&chksm=ec4aa741db3d2e572d04a2558d103be075e2f14cb039920857f17b0326ac7ff8841a794c63df&token=274586212&lang=zh_CN#rd)
    - ConcurrentHashMap：[ConcurrentHashMap的实现原理](https://blog.csdn.net/qq_40126996/article/details/105280871)
  
## 数据结构
 - 数组
 - 栈
 - 链表
   - 单链表
   - 双向链表
 - 树
   - 二叉树
   - 平衡二叉树
   - 红黑树
   - B-Tree
   - B+Tree
   
   
## 算法排序
 - 冒泡排序
 - 选择排序
 - 插入排序
 - 归并排序
 - 堆排序
 - 希尔排序
 - 桶排序
 - 计数排序
 - 基数排序
## MySQL：[MySQL知识点分析](https://blog.csdn.net/qq_40126996/article/details/106129661)
  - 存储引擎
    - InnoDB
    - MyIsAm
  - 事务
    - 原子性
    - 一致性
    - 隔离性
    - 持久性
  - 隔离级别
    - 读未提交
    - 读以提交
    - 可重复度
    - 可串行化
  - 索引
    - 结构
    - 类型
    - 聚簇
    - 非聚簇
    - 优化
  - 锁
    - 全局锁
    - 表锁
    - 行锁
    - 间隙锁
    - 读写锁
## 并发编程
  - 并发编程基础：[并发编程基础知识汇总](https://blog.csdn.net/qq_40126996/article/details/106044854)
    - 基础概念：[并发编程基础知识汇总二](https://blog.csdn.net/qq_40126996/article/details/106365971)
      - 并发
      - 并行
      - 线程
      - 进程
      - 线程安全
      - 死锁
    - 线程基础操作
      - 线程状态
        - 创建
        - 就绪
        - 运行
        - 阻塞
        - 死亡
      - 线程通信
        - Object类型
          - wait
          - notify
          - notifyAll
        - Thread类型
          - sleep
          - join
          - yield
      - Deamon守护线程
    - 锁类型：[锁类型分析](https://blog.csdn.net/qq_40126996/article/details/106462839)
      - 悲观锁
      - 乐观锁
      - 公平锁
      - 非公平锁
      - 独占锁
      - 共享锁
      - 自旋锁
      - 可重入锁
    - 并发关键字
      - volatile：[分析volatile的实现过程](https://blog.csdn.net/qq_40126996/article/details/106365971)，[volatile实现过程2](https://blog.csdn.net/qq_40126996/article/details/106201978)
      - synchronized：[分析synchronized的实现过程](https://blog.csdn.net/qq_40126996/article/details/106365971)，[synchronized实现过程2](https://blog.csdn.net/qq_40126996/article/details/106201978)
      - final
      - Atomic：[从源码分析Atomic](https://blog.csdn.net/qq_40126996/article/details/107169176)
    - 并发理论
      - 重排序
      - happens-before规则
      - 三大问题
    - Concurrent工具包
      - CountDownLatch：[CountDownLatch源码分析](https://blog.csdn.net/qq_40126996/article/details/107030573)
      - CycliBarrier：[CycliBarrier源码分析](https://blog.csdn.net/qq_40126996/article/details/107052600)
      - Semaphore：[Semaphore源码分析](https://blog.csdn.net/qq_40126996/article/details/107095239)
      - Exchange
    - 线程池：[线程池原理探究](https://mp.weixin.qq.com/s?__biz=MzI5NTk0MDkwNA==&mid=2247483682&idx=1&sn=97995d6169c00fd584da68d0363f3484&chksm=ec4aa765db3d2e7393e66cb660ef944fb33770600ec8b438ce2edc73da7f7731899ca6ecdb35&token=274586212&lang=zh_CN#rd)
      - 参数
        - corePoreSize
        - workQueue
        - maximunPoolSize
        - ThreadFactory
        - RejectedExecutionHandler
        - keeyAliveTime
        - TimeUnit
      - 状态
        - RUNNING
        - SHUTDOWN
        - STOP
        - TIDYING
        - TERMINATED
      - 类型
        - newCachedThreadPool
        - newFixedThreadPool
        - newSingleThreadExecutor
        - ScheduleThreadPool
    - CAS
    - Lock
      - AQS：[如何实现AQS同步队列器](https://blog.csdn.net/qq_40126996/article/details/106629938)
      - ReentrantLock：[ReentrantLock的实现原理](https://blog.csdn.net/qq_40126996/article/details/106751735)
      - ReentrantReadWriteLock：[ReentrantReadWriteLock的实现原理](https://blog.csdn.net/qq_40126996/article/details/106819495)
      - Condition机制
      - Lock与Synchronized
    - 并发容器
      - ConcurrentHashMap：[ConcurrentHashMap的实现原理](https://blog.csdn.net/qq_40126996/article/details/105280871)
      - ConcurrentSkipListMap
      - Queue
        - 单端阻塞（BlockingQueue）
        - 双端阻塞（BlockingDeque）
        - 单端非阻塞（Queue）
        - 双端非阻塞（Deque）
      - ThreadLocal：[从源码分析ThreadLocal的实现原理](https://blog.csdn.net/qq_40126996/article/details/107345176)
      
    
## 分布式组件
   - zookeeper
   - Dubbo
     - 核心功能
       - Remoting
       - Cluster
       - Registry
     - 核心组件
       - Provider
       - Consumer
       - Registry
       - Monitor
       - Container
     - 协议
       - dubbo
       - rmi
       - webservice
       - http
       - hessian
       - redis
       - memcache
     - 注册中心
       - Zookeeper
       - Multicast
       - Redis
       - Simple
     - 注册与发现流程
     - 负载均衡策略
       - RoundRobin LoadBalance（轮询选取提供者策略）
       - LeastActive LoadBalance（最少活跃调用策略）
       - ConstantHash LoadBalance（一致性hash策略）
     - 集群容错方案
       - Failover Cluster（失败自动切换模式）
       - Failfast Cluster（快速失败模式）
       - Failsafe Cluster（失败安全模式）
       - Failback Cluster（失败自动恢复模式）
       - Forking Cluster（并行模式）
       - Broadcast Cluster（广播模式）
     - 架构
       - 服务接口层（Service）
       - 配置层（Config）
       - 服务代理层（Proxy）
       - 服务注册层（Registry）
       - 集群层（Cluster）
       - 监控层（Monitor）
       - 远程调用层（Protocol）
       - 信息交换层（Exchange）
       - 网络传输层（Transport）
     - 通信框架
    
## 调优
   - JVM调优
   - 事务优化
   - 数据库优化
   - 内存溢出排查
   - I/O排查
   - 堆内存排查
      
      
 ## JVM
   - 类加载
     - 类加载过程
       - 加载
       - 检验
       - 准备
       - 解析
       - 初始化

     - 双亲委派
       - Bootstrap ClassLoader
       - Ext ClassLoader
       - Application ClassLoader
       - 过程

   - 内存区域
     - 堆
     - 方法区
     - 本地方法栈
     - 虚拟机栈
     - 程序计数器

   - 内存分配策略
     - 年轻代：执行Minor GC
       - 一个Eden区
       - 两个survivor区
         - From survivor
         - To survivor
     - 老年代：执行Full GC
       - 大对象会直接进入老年代
       - 长期存活的会进入老年代
       - 年龄超过阈值的会进入老年代

   - 判断回收对象算法
     - 可达性分析法
     - 引用计数法
     - 引用类型
       - 强引用
       - 弱引用
       - 软引用
       - 虚引用

   - 垃圾回收算法
     - 标记-清除算法
     - 复制算法
     - 标记-整理算法

   - 垃圾回收器
     - 新生代
     - 老年代
       - Serial Old
       - Parallel Old
       - CMS
       - G1
          
          
 ## 设计模式
   - 单例模式
     - 懒汉式
     - 饿汉式
   - 工厂模式
   - 代理模式
     - 静态代理
     - 动态代理
       - jdk动态代理
       - cglib动态代理

 ## 计算机网络
   - 三次握手
   - 四次挥手
   - TCP/IP五层模型
      
      
 ## 中间件
   - Redis
     - 数据结构
       - String
       - Hash
       - List
       - Set
       - ZSet
     - 缓存一致性
     - 缓存三大问题
       - 缓存雪崩
       - 缓存击穿
       - 缓存穿透
     - 分布式锁
     - 高可用
       - 集群

       - 持久化
         - AOF
         - RDB

       - 哨兵

   - RabbitMQ
     - 高可用
     - 模式
       - 队列模式
       - 工作模式
       - 订阅者模式
       - 路由模式
       - 主题模式
   - Kafka
      
 ## 网络通信
   - Netty
     - 组件
       - Selector
       - Channel
       - Buffer
 ## 分库分表
 ## 操作系统

 ![Image text](https://github.com/linglongchen/Java-knowledge/blob/master/image/%E5%90%8E%E7%AB%AF%E7%9F%A5%E8%AF%86%E6%9E%B6%E6%9E%84.png)

### 自己梳理的Java后端知识架构，后续会慢慢填补上对应的知识点，主要是为了应对以后的面试，也希望能给需要的人带来帮助，觉得可以的话希望给一个start。
### 自己整理的可能不全面，所以希望也能给予issue，万分感谢。

