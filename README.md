# java
## java面试总结

### java基础：
* 集合
    * list 
      `线程安全：`vector 
      `线程不安全：`ArrayList(数组) LinkedList(环形双向链表)<br>
      由于底层实现方式不同，不同的操作，效率也会有所不同<br>
      * 数组：查询快，增删慢
      * 链表：查询慢，增删块
    * set 
    * map <br>
    线程安全和不安全 为什么？
* 线程池的几个参数
* 锁
    * synchronized和Lock
    * 读写锁
    * 乐观锁  悲观锁   
    * validate关键字
* 内存模型 
    * string
    <br>`eg`<br>
    String s="abc"
    String s1=new String("abc")
    * javaGC
* 多线程
    * 种类 
    * 实现的方法 
    * 同步线程的方法  
    * wait和sleep的区别 notify run()有无返回值  join()  调度器
* 序列化implements serializable  
* 异常

* stringBuilder和stringBuffer
          
### javaweb:
          socket通信客户端与服务端         
### 数据库：
* 索引  
    * 聚合索引  
          `eg`
* 执行引擎 
* acid特性
* delete和truncate
### spring框架：
* springmvc工作原理 
* spring的事务隔离级别（传播行为）
* aop 
* ioc 
* 事务的原理  
### mybatis的批量插入
### 远程框架：
* dubbox的原理
### 计算机网络：
* rpc
* http
* 二者的差别
### 设计模式：
* 动态代理静态代理  
* 单例多例
### redis常用类型：
### 业务
* nginx中session如何共享
* 幂等性


