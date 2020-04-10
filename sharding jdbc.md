# sharding jdbc



## 简介



Sharding-JDBC 轻量级Java框架，JDBC层提供额外的服务，使用客户端直连db，以`jar包`形式提供服务，无需额外部署和依赖，可理解为增强版的JDBC驱动，完全兼容JDBC和各种`ORM框架`



适用于任何基于Java的ORM框架，如`JPA` `Hibernate` `Mybatis` `Spring JDBC Template` 或者`直接使用JDBC`



基于任何第三方的数据库连接池，如：`DBCP` `C3P0` `BoneCP` `Druid` `HikariCP`等

支持任意实现JDBC规范的数据库，目前支持`MySQL` `Oracle` `SQLServer` 和 `PostgreSQL`



## 功能

### 数据分片

#### 分库&分表

#### 读写分离

#### 分布式主键



### 分布式事务

#### XA强一致事务

#### 柔性事务



### 数据库治理

#### 配置动态化

#### 熔断&禁用

#### 调用链路追踪

#### 弹性伸缩（Planning）









##  数据分片



垂直切分 水平切分

---



分片键



分片算法



​		hint分片算法

​		

逻辑表



真实表



数据节点



绑定表



广播表

​		字典表



sql分开查询，结果归并，返回

引入maven依赖

数据库配置

分片策略配置

​	preciseSHardingAlgorithm

​	RangeShardingAlgorithm

​	ComplexKeysShardingAlgorithm

​	HintShardingAlgorithm



消息平台如何实现





1.maven依赖引入1

2.





配置多个库和表，相应