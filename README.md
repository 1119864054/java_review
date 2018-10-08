* [Spring相关](#spring%E7%9B%B8%E5%85%B3)
    * [spring 优点，特性](#spring-%E4%BC%98%E7%82%B9%E7%89%B9%E6%80%A7)
    * [spring IOC AOP，aop如何实现](#spring-ioc-aopaop%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
    * [JDK动态代理和cgLib动态代理](#jdk%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86%E5%92%8Ccglib%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86)
    * [sprin创建bean过程](#sprin%E5%88%9B%E5%BB%BAbean%E8%BF%87%E7%A8%8B)
    * [SpringMVC常用注解](#springmvc%E5%B8%B8%E7%94%A8%E6%B3%A8%E8%A7%A3)
    * [springMVC处理请求流程/工作流程](#springmvc%E5%A4%84%E7%90%86%E8%AF%B7%E6%B1%82%E6%B5%81%E7%A8%8B%E5%B7%A5%E4%BD%9C%E6%B5%81%E7%A8%8B)
    * [SpringMVC @RequestParam，@PathParam，@PathVariable等注解区别](#springmvc-requestparampathparampathvariable%E7%AD%89%E6%B3%A8%E8%A7%A3%E5%8C%BA%E5%88%AB)
    * [BeanFactory和FactoryBean区别](#beanfactory%E5%92%8Cfactorybean%E5%8C%BA%E5%88%AB)
    * [Spring事务配置](#spring%E4%BA%8B%E5%8A%A1%E9%85%8D%E7%BD%AE)
    * [SpringBoot面试题](#springboot%E9%9D%A2%E8%AF%95%E9%A2%98)
* [Java相关](#java%E7%9B%B8%E5%85%B3)
    * [三大特性：封装、继承、多态](#%E4%B8%89%E5%A4%A7%E7%89%B9%E6%80%A7%E5%B0%81%E8%A3%85%E7%BB%A7%E6%89%BF%E5%A4%9A%E6%80%81)
    * [抽象类和接口区别](#%E6%8A%BD%E8%B1%A1%E7%B1%BB%E5%92%8C%E6%8E%A5%E5%8F%A3%E5%8C%BA%E5%88%AB)
    * [Object类下的方法](#object%E7%B1%BB%E4%B8%8B%E7%9A%84%E6%96%B9%E6%B3%95)
    * [Collection类](#collection%E7%B1%BB)
    * [反射](#%E5%8F%8D%E5%B0%84)
    * [java多线程工具类（CountDownLatch等）](#java%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%B7%A5%E5%85%B7%E7%B1%BBcountdownlatch%E7%AD%89)
    * [Hibernate和Mybatis的区别](#hibernate%E5%92%8Cmybatis%E7%9A%84%E5%8C%BA%E5%88%AB)
    * [copyonrightArraylsit](#copyonrightarraylsit)
    * [同时重写equals和hashcode](#%E5%90%8C%E6%97%B6%E9%87%8D%E5%86%99equals%E5%92%8Chashcode)
    * [wait，notify，notifyall](#waitnotifynotifyall)
    * [arrayList和linkedList区别，使用场景](#arraylist%E5%92%8Clinkedlist%E5%8C%BA%E5%88%AB%E4%BD%BF%E7%94%A8%E5%9C%BA%E6%99%AF)
    * [hashmap，hashtable，concurrent hashmap，区别，源码，扩容](#hashmaphashtableconcurrent-hashmap%E5%8C%BA%E5%88%AB%E6%BA%90%E7%A0%81%E6%89%A9%E5%AE%B9)
    * [hashmap为什么会造成死循环](#hashmap%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E9%80%A0%E6%88%90%E6%AD%BB%E5%BE%AA%E7%8E%AF)
    * [解决hash冲突的办法](#%E8%A7%A3%E5%86%B3hash%E5%86%B2%E7%AA%81%E7%9A%84%E5%8A%9E%E6%B3%95)
    * [HashSet实现原理](#hashset%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
    * [联合索引在B\+树中是怎么存储的](#%E8%81%94%E5%90%88%E7%B4%A2%E5%BC%95%E5%9C%A8b%E6%A0%91%E4%B8%AD%E6%98%AF%E6%80%8E%E4%B9%88%E5%AD%98%E5%82%A8%E7%9A%84)
    * [OOM异常](#oom%E5%BC%82%E5%B8%B8)
    * [Synchronized使用方式](#synchronized%E4%BD%BF%E7%94%A8%E6%96%B9%E5%BC%8F)
    * [Synchronized、Lock、ReentrantLock的区别](#synchronizedlockreentrantlock%E7%9A%84%E5%8C%BA%E5%88%AB)
    * [synchronized和lock区别，底层实现](#synchronized%E5%92%8Clock%E5%8C%BA%E5%88%AB%E5%BA%95%E5%B1%82%E5%AE%9E%E7%8E%B0)
    * [volatile关键字，底层实现](#volatile%E5%85%B3%E9%94%AE%E5%AD%97%E5%BA%95%E5%B1%82%E5%AE%9E%E7%8E%B0)
    * [final、finally和finalize区别](#finalfinally%E5%92%8Cfinalize%E5%8C%BA%E5%88%AB)
    * [新建线程的几种方式，线程池，ThreadPoolExecutor各种参数](#%E6%96%B0%E5%BB%BA%E7%BA%BF%E7%A8%8B%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E5%BC%8F%E7%BA%BF%E7%A8%8B%E6%B1%A0threadpoolexecutor%E5%90%84%E7%A7%8D%E5%8F%82%E6%95%B0)
    * [JVM分区，GC算法](#jvm%E5%88%86%E5%8C%BAgc%E7%AE%97%E6%B3%95)
    * [string、stringBuffer和stringBuilder区别](#stringstringbuffer%E5%92%8Cstringbuilder%E5%8C%BA%E5%88%AB)
    * [==和equals区别](#%E5%92%8Cequals%E5%8C%BA%E5%88%AB)
    * [Java中锁的类型（互斥锁，同步锁，公平锁，非公平锁）](#java%E4%B8%AD%E9%94%81%E7%9A%84%E7%B1%BB%E5%9E%8B%E4%BA%92%E6%96%A5%E9%94%81%E5%90%8C%E6%AD%A5%E9%94%81%E5%85%AC%E5%B9%B3%E9%94%81%E9%9D%9E%E5%85%AC%E5%B9%B3%E9%94%81)
    * [虚拟机类加载机制，以及打破双亲委派模型](#%E8%99%9A%E6%8B%9F%E6%9C%BA%E7%B1%BB%E5%8A%A0%E8%BD%BD%E6%9C%BA%E5%88%B6%E4%BB%A5%E5%8F%8A%E6%89%93%E7%A0%B4%E5%8F%8C%E4%BA%B2%E5%A7%94%E6%B4%BE%E6%A8%A1%E5%9E%8B)
    * [sleep，wait方法（必须在while循环中使用）](#sleepwait%E6%96%B9%E6%B3%95%E5%BF%85%E9%A1%BB%E5%9C%A8while%E5%BE%AA%E7%8E%AF%E4%B8%AD%E4%BD%BF%E7%94%A8)
    * [CAS，AQS](#casaqs)
    * [git基本命令](#git%E5%9F%BA%E6%9C%AC%E5%91%BD%E4%BB%A4)
* [操作系统相关](#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E7%9B%B8%E5%85%B3)
    * [进程和线程的区别](#%E8%BF%9B%E7%A8%8B%E5%92%8C%E7%BA%BF%E7%A8%8B%E7%9A%84%E5%8C%BA%E5%88%AB)
    * [进程间的通信方式，线程间的通信方式](#%E8%BF%9B%E7%A8%8B%E9%97%B4%E7%9A%84%E9%80%9A%E4%BF%A1%E6%96%B9%E5%BC%8F%E7%BA%BF%E7%A8%8B%E9%97%B4%E7%9A%84%E9%80%9A%E4%BF%A1%E6%96%B9%E5%BC%8F)
    * [银行家算法，死锁解决方法](#%E9%93%B6%E8%A1%8C%E5%AE%B6%E7%AE%97%E6%B3%95%E6%AD%BB%E9%94%81%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95)
    * [页面置换算法](#%E9%A1%B5%E9%9D%A2%E7%BD%AE%E6%8D%A2%E7%AE%97%E6%B3%95)
    * [缺页中断，抖动问题](#%E7%BC%BA%E9%A1%B5%E4%B8%AD%E6%96%AD%E6%8A%96%E5%8A%A8%E9%97%AE%E9%A2%98)
    * [虚拟地址如何映射成物理地址，TLB](#%E8%99%9A%E6%8B%9F%E5%9C%B0%E5%9D%80%E5%A6%82%E4%BD%95%E6%98%A0%E5%B0%84%E6%88%90%E7%89%A9%E7%90%86%E5%9C%B0%E5%9D%80tlb)
    * [LRU（最近最少使用）](#lru%E6%9C%80%E8%BF%91%E6%9C%80%E5%B0%91%E4%BD%BF%E7%94%A8)
* [数据结构与算法](#%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8E%E7%AE%97%E6%B3%95)
    * [动态规划](#%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92)
    * [红黑树性质](#%E7%BA%A2%E9%BB%91%E6%A0%91%E6%80%A7%E8%B4%A8)
    * [排序算法（快速排序，希尔排序） 手写](#%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F%E5%B8%8C%E5%B0%94%E6%8E%92%E5%BA%8F-%E6%89%8B%E5%86%99)
    * [二分查找   手写](#%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE---%E6%89%8B%E5%86%99)
    * [链表相关（是否有环，环的头结点）](#%E9%93%BE%E8%A1%A8%E7%9B%B8%E5%85%B3%E6%98%AF%E5%90%A6%E6%9C%89%E7%8E%AF%E7%8E%AF%E7%9A%84%E5%A4%B4%E7%BB%93%E7%82%B9)
    * [二叉树，B/B\+树](#%E4%BA%8C%E5%8F%89%E6%A0%91bb%E6%A0%91)
    * [生产者消费者     手写](#%E7%94%9F%E4%BA%A7%E8%80%85%E6%B6%88%E8%B4%B9%E8%80%85%E6%89%8B%E5%86%99)
* [计算机网络相关](#%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C%E7%9B%B8%E5%85%B3)
    * [https和http，为什么https是安全的](#https%E5%92%8Chttp%E4%B8%BA%E4%BB%80%E4%B9%88https%E6%98%AF%E5%AE%89%E5%85%A8%E7%9A%84)
    * [https请求过程，http请求全过程](#https%E8%AF%B7%E6%B1%82%E8%BF%87%E7%A8%8Bhttp%E8%AF%B7%E6%B1%82%E5%85%A8%E8%BF%87%E7%A8%8B)
    * [http 1\.0 1\.1 2\.0 区别](#http-10-11-20-%E5%8C%BA%E5%88%AB)
    * [DNS域名解析过程](#dns%E5%9F%9F%E5%90%8D%E8%A7%A3%E6%9E%90%E8%BF%87%E7%A8%8B)
    * [TCP/IP协议，三次握手，四次挥手](#tcpip%E5%8D%8F%E8%AE%AE%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B)
    * [TCP的TIME\_WAIT状态](#tcp%E7%9A%84time_wait%E7%8A%B6%E6%80%81)
    * [ISO七层网络模型](#iso%E4%B8%83%E5%B1%82%E7%BD%91%E7%BB%9C%E6%A8%A1%E5%9E%8B)
    * [基于TCP和UDP的协议](#%E5%9F%BA%E4%BA%8Etcp%E5%92%8Cudp%E7%9A%84%E5%8D%8F%E8%AE%AE)
    * [常用端口号：](#%E5%B8%B8%E7%94%A8%E7%AB%AF%E5%8F%A3%E5%8F%B7)
    * [http状态码](#http%E7%8A%B6%E6%80%81%E7%A0%81)
    * [http请求头部](#http%E8%AF%B7%E6%B1%82%E5%A4%B4%E9%83%A8)
    * [tcp和udp区别，应用场景](#tcp%E5%92%8Cudp%E5%8C%BA%E5%88%AB%E5%BA%94%E7%94%A8%E5%9C%BA%E6%99%AF)
    * [get和post区别，各自优缺点](#get%E5%92%8Cpost%E5%8C%BA%E5%88%AB%E5%90%84%E8%87%AA%E4%BC%98%E7%BC%BA%E7%82%B9)
    * [Cookie和Session区别](#cookie%E5%92%8Csession%E5%8C%BA%E5%88%AB)
* [数据库相关](#%E6%95%B0%E6%8D%AE%E5%BA%93%E7%9B%B8%E5%85%B3)
    * [数据库三范式](#%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%89%E8%8C%83%E5%BC%8F)
    * [MySQL各种引擎，区别](#mysql%E5%90%84%E7%A7%8D%E5%BC%95%E6%93%8E%E5%8C%BA%E5%88%AB)
    * [MySQL四种事务隔离级别，以及ACID](#mysql%E5%9B%9B%E7%A7%8D%E4%BA%8B%E5%8A%A1%E9%9A%94%E7%A6%BB%E7%BA%A7%E5%88%AB%E4%BB%A5%E5%8F%8Aacid)
    * [数据库索引，什么情况下不走索引](#%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B4%A2%E5%BC%95%E4%BB%80%E4%B9%88%E6%83%85%E5%86%B5%E4%B8%8B%E4%B8%8D%E8%B5%B0%E7%B4%A2%E5%BC%95)
    * [索引的实现](#%E7%B4%A2%E5%BC%95%E7%9A%84%E5%AE%9E%E7%8E%B0)
    * [MySQL索引类型，索引种类](#mysql%E7%B4%A2%E5%BC%95%E7%B1%BB%E5%9E%8B%E7%B4%A2%E5%BC%95%E7%A7%8D%E7%B1%BB)
    * [B\+索引和hash索引区别](#b%E7%B4%A2%E5%BC%95%E5%92%8Chash%E7%B4%A2%E5%BC%95%E5%8C%BA%E5%88%AB)
    * [innodb为什么默认用b\+树索引](#innodb%E4%B8%BA%E4%BB%80%E4%B9%88%E9%BB%98%E8%AE%A4%E7%94%A8b%E6%A0%91%E7%B4%A2%E5%BC%95)
    * [limit使用](#limit%E4%BD%BF%E7%94%A8)
    * [\#\{\} $\{\}区别](#-%E5%8C%BA%E5%88%AB)
    * [如何消除幻读](#%E5%A6%82%E4%BD%95%E6%B6%88%E9%99%A4%E5%B9%BB%E8%AF%BB)
    * [inner join，left join，right join](#inner-joinleft-joinright-join)
    * [常用数据库连接池（DBCP,c3p0,druid）](#%E5%B8%B8%E7%94%A8%E6%95%B0%E6%8D%AE%E5%BA%93%E8%BF%9E%E6%8E%A5%E6%B1%A0dbcpc3p0druid)
    * [explain查看数据库执行语句的效率](#explain%E6%9F%A5%E7%9C%8B%E6%95%B0%E6%8D%AE%E5%BA%93%E6%89%A7%E8%A1%8C%E8%AF%AD%E5%8F%A5%E7%9A%84%E6%95%88%E7%8E%87)
    * [JDBC步骤](#jdbc%E6%AD%A5%E9%AA%A4)
    * [Redis数据类型](#redis%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B)
    * [redis持久化（RDB AOF）](#redis%E6%8C%81%E4%B9%85%E5%8C%96rdb-aof)
    * [redis过期策略](#redis%E8%BF%87%E6%9C%9F%E7%AD%96%E7%95%A5)
* [设计模式相关](#%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F%E7%9B%B8%E5%85%B3)
    * [单例模式（懒汉式，饿汉式等） 手写        <a href="%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F%E7%9B%B8%E5%85%B3/%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F\.md">(check)</a>](#%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F%E6%87%92%E6%B1%89%E5%BC%8F%E9%A5%BF%E6%B1%89%E5%BC%8F%E7%AD%89-%E6%89%8B%E5%86%99check)
    * [工厂模式 <a href="%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F%E7%9B%B8%E5%85%B3/%E5%B7%A5%E5%8E%82%E6%A8%A1%E5%BC%8F\.md">(check)</a>](#%E5%B7%A5%E5%8E%82%E6%A8%A1%E5%BC%8Fcheck)
    * [代理模式](#%E4%BB%A3%E7%90%86%E6%A8%A1%E5%BC%8F)
    * [适配器模式](#%E9%80%82%E9%85%8D%E5%99%A8%E6%A8%A1%E5%BC%8F)
    * [装饰者模式](#%E8%A3%85%E9%A5%B0%E8%80%85%E6%A8%A1%E5%BC%8F)

# Spring相关

### spring 优点，特性

​		https://www.cnblogs.com/song1314/articles/4568379.html

### spring IOC AOP，aop如何实现

​		https://www.cnblogs.com/superjt/p/4311577.html
​		http://www.cnblogs.com/hongwz/p/5764917.html

### JDK动态代理和cgLib动态代理

​		https://www.ibm.com/developerworks/cn/java/j-lo-proxy-pattern/
​		https://blog.csdn.net/DoUUnderstand/article/details/78865385
​		https://www.cnblogs.com/bigmonkeys/p/7823268.html

### sprin创建bean过程

​		https://blog.csdn.net/qq_18860653/article/details/53218117
​		https://blog.csdn.net/hsj1213522415/article/details/78166741

### SpringMVC常用注解

​		https://blog.csdn.net/wuruijiang/article/details/78970547

### springMVC处理请求流程/工作流程

​		https://www.cnblogs.com/leskang/p/6101368.html
​		https://www.cnblogs.com/hujiapeng/p/5765636.html

### SpringMVC @RequestParam，@PathParam，@PathVariable等注解区别

​		https://blog.csdn.net/u011410529/article/details/66974974

### BeanFactory和FactoryBean区别

​		https://blog.csdn.net/wangbiao007/article/details/53183764

### Spring事务配置

​		https://blog.csdn.net/bao19901210/article/details/41724355

### SpringBoot面试题

​		http://www.3xmq.com/article/1522809264295
​	
​	

# Java相关

### 三大特性：封装、继承、多态

​		https://blog.csdn.net/o_ozbl/article/details/79580287

### 抽象类和接口区别

​		https://blog.csdn.net/jjjjjj123321/article/details/54135413

### Object类下的方法

​		https://blog.csdn.net/u013894427/article/details/53468038

### Collection类

​		https://blog.csdn.net/oguro/article/details/53413861

### 反射

​		https://www.cnblogs.com/ysocean/p/6516248.html
​		https://blog.csdn.net/codejas/article/details/78635926

### java多线程工具类（CountDownLatch等）

​		https://blog.csdn.net/p106786860/article/details/52686245

### Hibernate和Mybatis的区别

​		https://blog.csdn.net/w_q_q_/article/details/79032062

### copyonrightArraylsit

​		https://www.cnblogs.com/biyeymyhjob/archive/2012/07/20/2601655.html
​		https://blog.csdn.net/wjwj1203/article/details/8109000

### 同时重写equals和hashcode

​		http://www.cnblogs.com/shenliang123/archive/2012/04/16/2452206.html

### wait，notify，notifyall

​		https://blog.csdn.net/vk5176891/article/details/53945677

### arrayList和linkedList区别，使用场景

​		https://blog.csdn.net/qq_32679815/article/details/78907437

### hashmap，hashtable，concurrent hashmap，区别，源码，扩容

​		https://www.cnblogs.com/zx-bob-123/archive/2017/12/26/8118074.html

### hashmap为什么会造成死循环

​		https://blog.csdn.net/silyvin/article/details/79102415

### 解决hash冲突的办法

​		https://blog.csdn.net/qq_27093465/article/details/52269862

### HashSet实现原理

​		https://blog.csdn.net/weixin_28953659/article/details/80481886

### 联合索引在B+树中是怎么存储的

​		https://blog.csdn.net/weixin_30531261/article/details/79329722

### OOM异常

​		https://blog.csdn.net/sinat_29912455/article/details/51125748

### Synchronized使用方式

​		https://blog.csdn.net/sinat_32588261/article/details/72880159
​		https://blog.csdn.net/luoweifu/article/details/46613015

### Synchronized、Lock、ReentrantLock的区别

​		https://blog.csdn.net/hunterliy/article/details/53954197

### synchronized和lock区别，底层实现

​		https://blog.csdn.net/u012403290/article/details/64910926

### volatile关键字，底层实现

​		https://blog.csdn.net/ismahui/article/details/75726188
​		http://www.cnblogs.com/jinshuai86/p/9226164.html

### final、finally和finalize区别

​		

### 新建线程的几种方式，线程池，ThreadPoolExecutor各种参数

​		https://blog.csdn.net/u012973218/article/details/51280044
​		https://blog.csdn.net/qq_34952110/article/details/78086085
​		https://www.cnblogs.com/waytobestcoder/p/5323130.html

### JVM分区，GC算法

​	

### string、stringBuffer和stringBuilder区别

​		https://www.cnblogs.com/su-feng/p/6659064.html

### ==和equals区别

​		《深入理解Java虚拟机》

### Java中锁的类型（互斥锁，同步锁，公平锁，非公平锁）

​		https://www.cnblogs.com/qifengshi/p/6831055.html
​		https://blog.csdn.net/g1607058603/article/details/80893711

### 虚拟机类加载机制，以及打破双亲委派模型

​		《深入理解Java虚拟机》P209
​		http://www.importnew.com/25295.html

### sleep，wait方法（必须在while循环中使用）

​		wait()会释放对象锁而sleep()不会释放对象锁

### CAS，AQS

### git基本命令

​	

# 操作系统相关

### 进程和线程的区别

### 进程间的通信方式，线程间的通信方式

​		进程：可并发执行的，具有独立功能的程序在一定数据集合上的一次执行过程，是操作系统进行资源分配和调度的基本单位。（管道，FIFO，消息队列，信号量，共享内存，套接字）
​		线程：操作系统中能够独立执行的实体，是进程的组成部分，是处理器调度的基本单位。（共享内存，wait/notify，管道，lock/condition）

### 银行家算法，死锁解决方法

### 页面置换算法

### 缺页中断，抖动问题

### 虚拟地址如何映射成物理地址，TLB

### LRU（最近最少使用）

​	
​	

# 数据结构与算法

### 动态规划

​		https://www.cnblogs.com/CodingAndRiding/p/7619759.html

### 红黑树性质

### 排序算法（快速排序，希尔排序） 手写

### 二分查找   手写

### 链表相关（是否有环，环的头结点）

### 二叉树，B/B+树

### 生产者消费者	手写

​	
​	

# 计算机网络相关

### https和http，为什么https是安全的

​		https://blog.csdn.net/feilzhang/article/details/80554328

### https请求过程，http请求全过程

​		https://blog.csdn.net/yezitoo/article/details/78193794

### http 1.0 1.1 2.0 区别

​		https://blog.csdn.net/linsongbin1/article/details/54980801

### DNS域名解析过程

​		https://blog.csdn.net/m0_37812513/article/details/78775629

### TCP/IP协议，三次握手，四次挥手

​		https://blog.csdn.net/qzcsu/article/details/72861891

### TCP的TIME_WAIT状态

### ISO七层网络模型

​		应用层（HTTP，FTP，SMTP，DNS，TELNET，HTTPS，POP3，DHCP）

​		表示层（JPEG，ASCII）

​		会话层

​		传输层（TCP，UDP）网络层（IP，ICMP，ARP）

​		链路层

​		物理层

### 基于TCP和UDP的协议

​		TDP：HTTP，FTP，SMTP，TELNET，POP3
​		UDP：DNS，SNMP

### 常用端口号：

​		21：FTP连接
​		20：FTP数据传输
​		22：SSH
​		80：HTTP，NGINX
​		443：HTTPS
​		23：TELNET
​		8080：WWW

### http状态码

​		https://blog.csdn.net/q1056843325/article/details/53147180

### http请求头部

### tcp和udp区别，应用场景

​		https://blog.csdn.net/xiaobangkuaipao/article/details/76793702

### get和post区别，各自优缺点

​		https://blog.csdn.net/qq_26360877/article/details/70665820

### Cookie和Session区别

​		https://www.cnblogs.com/shiyangxt/articles/1305506.html
​	
​	

# 数据库相关

### 数据库三范式

​		1NF：每一列属性不可再分（原子性）
​		2NF：满足1NF，所有列依赖于主键
​		3NF：满足2NF，每列与主键直接相关，不是间接相关

### MySQL各种引擎，区别

​		https://blog.csdn.net/silyvin/article/details/79332879

### MySQL四种事务隔离级别，以及ACID

​		https://www.cnblogs.com/huanongying/p/7021555.html

### 数据库索引，什么情况下不走索引

​		https://www.cnblogs.com/shynshyn/p/7887742.html

### 索引的实现

​		https://blog.csdn.net/waeceo/article/details/78702584

### MySQL索引类型，索引种类

​		https://blog.csdn.net/liutong123987/article/details/79384395

### B+索引和hash索引区别

​		https://www.cnblogs.com/ziqiumeng/p/7680204.html

### innodb为什么默认用b+树索引

​		https://blog.csdn.net/xuehuagongzi000/article/details/78985844

### limit使用

​		https://blog.csdn.net/sinat_36246371/article/details/54582904

### #{} ${}区别

​		https://blog.csdn.net/lohannes/article/details/79031435

### 如何消除幻读

​		串行化，MVCC
​		https://blog.csdn.net/fanghanwen_fei/article/details/77884891

### inner join，left join，right join

### 常用数据库连接池（DBCP,c3p0,druid）

### explain查看数据库执行语句的效率

### JDBC步骤

​		https://www.cnblogs.com/jhcelue/p/6852258.html

### Redis数据类型

​		http://www.runoob.com/redis/redis-data-types.html

### redis持久化（RDB AOF）

​		https://blog.csdn.net/u010785685/article/details/52366977
​		https://www.cnblogs.com/AndyAo/p/8135980.html

### redis过期策略

​		https://www.cnblogs.com/xuliangxing/p/7151812.html
​	
​	

# 设计模式相关

### 单例模式（懒汉式，饿汉式等） 手写	[(check)](设计模式相关/单例模式.md)

​		https://www.cnblogs.com/hupp/p/4487521.html

### 工厂模式	[(check)](设计模式相关/工厂模式.md)

### 代理模式

### 适配器模式

### 装饰者模式