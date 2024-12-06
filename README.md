# Apache Kafka with GO

Using Sarama by IBM. This library is very stable, provides a lot of functionality and can 100% be used in production.

## Resources

-[Jay Kim article on Kafka](https://jskim1991.medium.com/docker-docker-compose-example-for-kafka-zookeeper-and-schema-registry-c516422532e7).
-[IBM sarama](https://github.com/IBM/sarama).

## Setup

1. Install Docker and Docker Compose

2. Run `docker-compose up -d` in the root directory. This will start Apache Kafka and Zookeeper

3. Install dependencies

4. Run go run `producer/producer.go` to start the producer which is a REST API listening on port 3000

5. Run go run `worker/worker.go` to start the consumer
