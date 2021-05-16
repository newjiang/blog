# 锁的分类

​		开始之前，先来回忆一下自己锁知道的锁有什么？可以的话，把它们罗列出来，并分析梳理它们之间的关系。例如我，首先想到的是synchronized，它关于锁的字眼就很多了，如锁的升级过程（无锁-偏向锁-轻量级锁-自旋锁-重量级锁），从特性上看可以是可重入锁，不可中断锁，非公平锁，独占锁，阻塞锁和悲观锁，还有对象锁，类锁。从数据库上看的时候，比如MySQL会有行锁，表锁，共享锁，排他锁，意向共享锁（IS锁）和意向排他锁（IX锁）等等。

​		那么锁的分类到底有多少种，我想很难给出一个标准的答案，不同业务里会有不同的要求，如果有人给这类业务场景定义了一个标准，便又诞生了新的锁。如果可以，同心锁是不是锁呢。废话结束讲正事，这些锁的特性往往的基于一种业务要求而诞生的，所以分类的话，就看从什么角度区分了。讲这么多，主要也想说明靠强记是很累的。下面是一张脑图，基于一些主要类型进行分类：

<img src="../img/01-锁的分类.png" alt="锁的分类"  />



下面是对其中的概念进行解释：

- 悲观锁/乐观锁：

  

- 共享锁/独占锁：

  

- 阻塞锁/非阻塞：

  

- 公平锁/非公平锁：

  

- 可重入锁/可重入锁：

  



# 分布式锁的背景



# 基于Zookeeper的分布式锁



# 基于Redis的分布式锁



# Zookeeper与RediK实现的对比