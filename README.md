# How to log all rabbitmq messages?

## Tracing

```
rabbitmqctl trace_on
rabbitmq-plugins enable rabbitmq_tracing
```
and `restart rabbitmq`

or
```
docker-compose up -d
```

## Test

sending a message
```
node send.js
```

## References

- http://www.mikeobrien.net/blog/tracing-rabbitmq-messages
- http://www.rabbitmq.com/firehose.html
- https://www.rabbitmq.com/tutorials/tutorial-one-javascript.html


