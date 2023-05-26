# springboot-kafka-real-world-project

# SpringBoot-ApacheKafka

Apache Kafka is a messaging queue service between microservice
==

Microservice1 (produce) ----->  Kafka broker <------ Microservice2 (consume)
============================================================================

![image](https://github.com/pavankumar0077/SpringBoot-ApacheKafka/assets/40380941/4d70a6f7-742d-4123-8f98-04f12eb3e2e4)

Apache Kafka
============
Kafka is distributed streaming platform means apache kafka can acts as a cluster so that it can contains one or more kafka brokers and it is fault tolerance - means if one node or a broker goes down then it can have capability to manage the other nodes as well becuase the data is distributed among different kafka brokers.

Producer 
=========
Producer is nothing but application that produces the message and send that message to kafka broker, producer can produce any kind of message like message can be event message can be a stream of records, stream of data, event can be plain text, json.

Consumer
========
Consumer will consume those messages from kafka broker 

topic
=====
Basically we create a topic in kafka cluster so that a consumer can able to subscribe to that particular topic.

zookeeper
=========
Zookeeper basically manages all the kafka broker states, Kafka cluster contains lof of brokers so zookeeper will manages and maintains all the brokder states and it maintains all the cofiguration of producers and consumers

reference link : https://www.javaguides.net/2022/06/spring-boot-apache-kafka-tutorial.html
reference link : https://kafka.apache.org/intro


