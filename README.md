# 🌱 Spring-Cloud-Kafka-Broker

This repository contains the implementation of a Kafka Broker using Spring Cloud. 

## 🚀 Getting Started

### 🐾 Running Zookeeper

Zookeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

!Zookeeper

### 🎈 Running Kafka

Kafka is a distributed streaming platform designed to build real-time pipelines and can be used as a message broker or as a replacement for a log aggregation solution.

!Kafka

## 📚 Features

### 📫 Topic - Consumer/Producer

A Kafka Topic is a stream of records ("/orders", "/user-signups"). You can think of a Topic as a feed name. A topic has a Log which is the topic’s storage on disk.

!Topic

### 📄 Default JSON Serialization

Serialization is the process of converting an object into a stream of bytes to store the object or transmit it to memory, a database, or a file. 

!Serialization

### 📮 PageEvent Receipt

PageEvent Receipt is a feature that allows you to track the events on your website.

!PageEvent Receipt
!PageEvent Receipt

### 📤 Sending Messages by Supplier

A Supplier is a simple interface with a single method that has no arguments and returns a result.

!Supplier

## ⏱ Real Time (Stream) Processing - Using Kafka Streams

Kafka Streams is a client library for building applications and microservices, where the input and output data are stored in Kafka clusters.

### 🔄 Function that receives input stream, process it, and produce an output stream

```bash
start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R4 --property print.key=true --property print.value=true --property key.deserializer=org.apache.kafka.common.serialization.StringDeserializer --property value.deserializer=org.apache.kafka.common.serialization.StringDeserializer

### 📊 Statistic about number of visitors each 100ms

![Statistics](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/fe464a6b-a031-4a61-beff-f36ec1866226)

### 📈 Data from Store (number of page, number of visits)

![Data from Store](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/5e7b4d96-90e5-4735-b9b2-46f17f4ef009)

### 🎨 Visual Representation using SmoothieJS

SmoothieJS is a simple, lightweight, and easy-to-use JavaScript library for smooth scrolling animations.

![SmoothieJS](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/1b716314-b84c-48da-8879-a6fbd6cc22bd)
```
I hope this helps! Let me know if you need further assistance.

Source: Conversation with Bing, 1/4/2024
(1) github.com. https://github.com/HouariZegai/java-learning/tree/6351291aab737b8d0e81f1e1273baac0a312beae/spring%2Fspring-cloud-streams-kafka%2FREADME.md.
