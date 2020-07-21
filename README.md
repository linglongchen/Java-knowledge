# Java-knowledge
 <p align="center">
<!--   <a href="#微信"><img src="https://img.shields.io/badge/weChat-微信群-blue.svg" alt="微信群"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-三太子敖丙-lightgrey.svg" alt="公众号"></a>
  <a href="https://space.bilibili.com/130763764"><img src="https://img.shields.io/badge/bilibili-哔哩哔哩-critical" alt="投稿"></a>
  <a href="https://www.toutiao.com/c/user/3270187212/#mid=1557137040287746"><img src="https://img.shields.io/badge/toutiao-头条-9cf" alt="投稿"></a>
  <a href="https://juejin.im/user/59b416065188257e671b670a"><img src="https://img.shields.io/badge/juejin-掘金-blue.svg" alt="公众号"></a>
  <a href="https://www.zhihu.com/people/aobingJava/activities"><img src="https://img.shields.io/badge/zhihu-知乎-informational" alt="投稿"></a>
  <a href="https://me.csdn.net/qq_35190492"><img src="https://img.shields.io/badge/csdn-CSDN-red.svg" alt="投稿"></a>
  <a href="https://my.oschina.net/javaFamily"><img src="https://img.shields.io/badge/oschina-开源中国-green" alt="投稿"></a>
  <a href="https://www.cnblogs.com/aobing/"><img src="https://img.shields.io/badge/cnblogs-博客园-important.svg" alt="投稿"></a> -->
</p>
## Spring
 - IOC：[Spring中IOC知识点介绍](https://mp.weixin.qq.com/s?__biz=MzI5NTk0MDkwNA==&mid=2247483703&idx=1&sn=c409488c95870d367162923075fed2cc&chksm=ec4aa770db3d2e6652c0c77cdf26a37dc6ea2a2486020ab9b632ec82f4bc0fa2c40290ffa396&scene=126&sessionid=1595328353&key=de438a290b06e75a5e8ee474df644893b6e0dcb29e2b34dc49617ea5d5adcbbf6af01f91a947036fe9805bb6b1ffb1a8d31982f7bc4f6f404231a20db9d0d29bb8aa2114159a01452bba955d137607cf&ascene=1&uin=MzU1MjE3NTAy&devicetype=Windows+10+x64&version=62090529&lang=zh_CN&exportkey=AeOFXcRKpXW5Blt9JlAJT2s%3D&pass_ticket=%2FJDJX3%2FxUFIRv8nz2s3qp6eYjByCRxZIquJcbqP%2Bv1Qq3X92dpF8p6Rl6QM1QGL4)
 - AOP：[Spring中AOP知识点介绍](https://mp.weixin.qq.com/s?__biz=MzI5NTk0MDkwNA==&mid=2247483666&idx=1&sn=488079b58f2387ee45b18f451eddb648&chksm=ec4aa755db3d2e43531e9a2ba4cc0ce64344c7bf9843dcea1613694db2fdaee4358b36f16b9c&token=200295296&lang=zh_CN#rd)
 
## 集合
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
    - ConcurrentHashMap
  
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
## MySQL
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
  - 并发编程基础
    - 基础概念
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
    - 锁类型
      - 悲观锁
      - 乐观锁
      - 公平锁
      - 非公平锁
      - 独占锁
      - 共享锁
      - 自旋锁
      - 可重入锁
    - 并发关键字
      - volatile
      - synchronized
      - final
      - Atomic
    - 并发理论
      - 重排序
      - happens-before规则
      - 三大问题
    - Concurrent工具包
      - CountDownLatch
      - CycliBarrier
      - Semaphore
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
      - AQS
      - ReentrantLock
      - ReentrantReadWriteLock
      - Condition机制
      - Lock与Synchronized
    - 并发容器
      - ConcurrentHashMap
      - ConcurrentSkipListMap
      - Queue
        - 单端阻塞（BlockingQueue）
        - 双端阻塞（BlockingDeque）
        - 单端非阻塞（Queue）
        - 双端非阻塞（Deque）
      - ThreadLocal
      
    
    
    

 ![Image text](https://github.com/linglongchen/Java-knowledge/blob/master/image/%E5%90%8E%E7%AB%AF%E7%9F%A5%E8%AF%86%E6%9E%B6%E6%9E%84.png)

### 自己梳理的Java后端知识架构，后续会慢慢填补上对应的知识点，主要是为了应对以后的面试，也希望能给需要的人带来帮助，觉得可以的话希望给一个start。
### 自己整理的可能不全面，所以希望也能给予issue，万分感谢。

