# 🌱 Spring-Cloud-Kafka-Broker

This repository contains the implementation of a Kafka Broker using Spring Cloud. 

## 🚀 Getting Started

### 🐾 Running Zookeeper

Zookeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

![cmd_U0Q5SkfM48](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/93e44ba5-eaf8-44a5-960e-c0cf2788bdb4)

### 🎈 Running Kafka

Kafka is a distributed streaming platform designed to build real-time pipelines and can be used as a message broker or as a replacement for a log aggregation solution.

![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/54efce05-4aa5-44ac-a5ec-8592d64d9f56)

## 📚 Features

### 📫 Topic - Consumer/Producer

A Kafka Topic is a stream of records. You can think of a Topic as a feed name. A topic has a Log which is the topic’s storage on disk.

![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/05e0aead-a63f-46cb-a650-6bdbb581ca5d)

### 📄 Default JSON Serialization

Serialization is the process of converting an object into a stream of bytes to store the object or transmit it to memory, a database, or a file. 

![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/74d2f37a-1bcd-4f36-873f-d150087d790b)

### 📮 PageEvent Receipt

PageEvent Receipt is a feature that allows you to track the events on your website.

![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/b8cf9984-5fe4-4b04-a250-72f178b3737c)
![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/180f7890-353e-432b-9c3e-f52de1ff4e09)

### 📤 Sending Messages by Supplier

A Supplier is a simple interface with a single method that has no arguments and returns a result.

![cmd_YWPuYbUPuU](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/b73aa0cb-a43e-49ef-9c9d-d5bdb832039e)

## ⏱ Real Time (Stream) Processing - Using Kafka Streams

Kafka Streams is a client library for building applications and microservices, where the input and output data are stored in Kafka clusters.

### 🔄 Function that receives input stream, process it, and produce an output stream

```bash
start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R4 --property print.key=true --property print.value=true --property key.deserializer=org.apache.kafka.common.serialization.StringDeserializer --property value.deserializer=org.apache.kafka.common.serialization.LongDeserializer
```

### 📊 Statistic about number of visitors each 100ms

![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/fe464a6b-a031-4a61-beff-f36ec1866226)

### 📈 Data from Store (number of page, number of visits)

![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/5e7b4d96-90e5-4735-b9b2-46f17f4ef009)

### 🎨 Visual Representation using SmoothieJS

SmoothieJS is a simple, lightweight, and easy-to-use JavaScript library for smooth scrolling animations.

![image](https://github.com/karamyf/Spring-Cloud-Kafka-Broker/assets/91606912/1b716314-b84c-48da-8879-a6fbd6cc22bd)
