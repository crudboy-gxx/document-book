# 第一部分 共享服务体系为业务带来的价值（what、why）

# 第二部分 共享服务体系搭建（how）

## 第三章 分布式服务框架的选择
### 3.1 淘宝平台服务化历程
+ 1、几百人维护一个war包模式带来的问题
+ 2、解决以上问题的方式：业务拆分（SOA理念）
+ 3、服务化是如何解决问题的
### 3.2 中心化和去中心化服务框架的对比
+ SOA的主要特性
+ 1、两套架构解决企业的根本诉求不同：异构系统之间交互与解决系统扩展性问题
+ 2、为什么中心化服务框架不适合互联网场景？
### 3.3 阿里巴巴分布式服务框架HSF
+ 1、介绍HFS框架主要组件
+ 2、HFS框架工作原理和架构设计
+ 3、HFS框架容错机制和线性扩展
### 3.4 关于微服务
+ 1、微服务的典型特征
+ 2、传统SOA与微服务对比
+ 3、docker容器技术优势，以及与微服务的结合
+ 4、微服务化过程要解决的问题


## 第四章 共享服务中心建设原则
### 4.1 淘宝的共享服务中心概貌
+ 1、四大服务中心介绍
### 4.2 什么是服务中心
+ 1、介绍服务中心特性
### 4.3 服务中心的划分原则
+ 服务中心建设的目的
+ 从设计、运营、工程三个维度来决定服务中心的设计和评估
+ 实际项目中总结的一些基本原则


## 第五章 数据拆分实现数据库能力线性扩展
### 5.1 数据库瓶颈阻碍业务的持续发展
+ 垂直分库方式的解决的问题和瓶颈
+ 读写分离方式的解决的问题和瓶颈
+ 水平分区方式的解决的问题和瓶颈
### 5.2 数据库分库分表的实践
+ 分布式数据层平台发展和演变
	+ Cobar数据库产生和问题
	+ 分布式数据层架构TDDL的产生和解决的问题
	+ TDDL架构和sql请求处理流
	+ DRDS的产生和解决的问题
+ 数据尽可能平均拆分
+ 尽量减少事务边界
+ 异构索引表尽量降低全表扫描频率
	+ 精卫数据库同步中间件
+ 将多条件频繁查询引入搜索引擎


## 第六章 异步化与缓存原则
### 6.1 业务流程异步化
+ 阿里异步化的典型场景和处理方式
### 6.2 数据库事务异步化
+ p2p还款场景下的问题和处理方式
### 6.3 事务与柔性事务
+ 保证业务事务一致性问题的解决方案
+ CAP理论
+ BASE理论

## 第七章 打造数字化运营能力