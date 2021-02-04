```
kafka-console-consumer --topic test-topic --from-beginning --consumer.config=consumer.properties --bootstrap-server=localhost:9092 
```


```
kafka-console-producer  --producer.config=producer.properties --topic test-topic
```


#### Do not forget to configure a `krb5.conf` in `/etc/krb5.conf`