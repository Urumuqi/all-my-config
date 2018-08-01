## Kafka Topic 常量定义

* const int32_t RdKafka::Topic::PARTITION_UA = -1
```en
Unassigned partition.

The unassigned partition is used by the producer API for messages that should be partitioned using the configured or default partitioner.
```

```cn
未分配的分区
bala ~~~~~
```

* const int64_t RdKafka::Topic::OFFSET_BEGINNING = -2
```en
Special offsets.

Consume from beginning
```

* const int64_t RdKafka::Topic::OFFSET_END = -1
```en
Consume from end
```

* const int64_t RdKafka::Topic::OFFSET_STORED = -1000
```en
Use offset storage
```
