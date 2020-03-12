# MQ 设计开发

> * 如何解决重复消费?
> * 如何保证消息的可靠性传输?
> * 如何保证消息有序？
> * 有几百万消息持续积压几小时怎么解决? 

* 如何让一个topic的消息，能够被多个消费者实例消费？
* 如何让MQ、生产者、消费者能够自动发现对方？
* 如何实现集群？

* 消息的顺序性
* 消息的ACK机制
* 最终一致性的设计
* 消息的事务支持
* 需要解决的问题

* ***[专治MQ中间件各种疑难杂症](https://www.toutiao.com/a6660630694026281480/)***


## [MQ Model](MQModel/README.md)

## 详细设计

### 消息投递策略
### [消息投递语义(Message Delivery Semantics)](Scheme/MessageDeliverySemantics.md)
### [Push or Pull]((Scheme/PushOrPull.md))
### 消息时序性
### 消息幂等性

## 协议设计

## 高可用设计
### 可扩展
### 多租户
### 持久化
### 流量控制
### 失败重试

## API 设计
