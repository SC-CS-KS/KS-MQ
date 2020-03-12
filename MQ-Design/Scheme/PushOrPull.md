# Push or Pull

## push
```text
优点：延时小，几乎可以做到实时
缺点：消费者端不好做流控 很难做批量推送，不知道要推送多少合适
解决思路: nsq的流控策略
```

## pull
```text
优点：消费者可以自己把握节奏
缺点：
  延时大
  消费者可能经常有空pull，即pull不到消息，造成浪费
解决思路：Kafka采用的是阻塞式pull
```

## 参考 
[Kafka: Push vs Pull](https://kafka.apache.org/documentation/#design_pull)
