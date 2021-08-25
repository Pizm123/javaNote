### 1、什么是 Spring Cloud？

　　Spring cloud 流应用程序启动器是基于 Spring Boot 的 Spring 集成应用程序，提供与外部系统的集成。Spring cloud Task，一个生命周期短暂的微服务框架，用于快速构建执行有限数据处理的应用程序。

### 2、Spring cloud的优点

### 3、Springboot和spring cloud的区别。



### 4、spring cloud 断路器的作用是什么？

​	在分布式环境下，特别是微服务结构的分布式系统中， 一个软件系统调用另外一个远程系统是非常普遍的。这种远程调用的被调用方可能是另外一个进程，或者是跨网路的另外一台主机, 这种远程的调用和进程的内部调用最大的区别是，远程调用可能会失败，或者挂起而没有任何回应，直到超时。更坏的情况是， 如果有多个调用者对同一个挂起的服务进行调用，那么就很有可能的是一个服务的超时等待迅速蔓延到整个分布式系统，引起连锁反应， 从而消耗掉整个分布式系统大量资源。最终可能导致系统瘫痪。
断路器（Circuit Breaker）模式就是为了防止在分布式系统中出现这种瀑布似的连锁反应导致的灾难。Hystrix 具备服务降级、服务熔断、线程和信号隔离、请求缓存、请求合并以及服务监控等强大功能,

### 5、Hystrix 的三种状态，工作原理


https://blog.csdn.net/qq_41347385/article/details/106044175?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromBaidu-1.control&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromBaidu-1.control


ribbon和feign区别  （负载均衡）
https://www.cnblogs.com/xiaofeng-fu/p/12119125.html

https://www.cnblogs.com/zhangkaimin/p/12068076.html