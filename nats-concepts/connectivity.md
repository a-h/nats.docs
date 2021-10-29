# NATS connectivity

NATS supports several kinds of connectivity _directly_ to the nats servers

* Plain NATS connections
* TLS encrypted NATS connections
* [WebSocket](https://github.com/nats-io/nats.ws) NATS connections
* [MQTT](/nats-server/configuration/mqtt/) client connections

There is also a number of adapters available to bridge traffic to and from other messaging systems

* [Kafka Bridge](https://github.com/nats-io/nats-kafka)
* [JMS](https://github.com/nats-io/nats-jms-bridge) which can also be used to bridge MQ and RabbitMQ, since they both offer a JMS interface