# Lock 和 Latch 的区别

## 概述

#### 锁定对象

* Lock: 事务
* Latch: 线程

#### 锁定持续时间

* Lock: 整个事务过程
* Latch: 临界资源持有过程

#### 模式

* Lock: 行锁, 表锁, 意向锁
* Latch: 读写锁, 互斥量

####  死锁

* Lock: 只能死锁检测
* Latch: 无死锁检车与处理机制