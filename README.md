# Real-Time-Data-Processing-with-Confluent-Kafka-PostgreSQL-and-Avro

## 1. Objective:
In this assignment, you will build a Kafka producer and a consumer group that work with a PostgreSQL database, Avro serialization, and multi-partition Kafka topics. 
The producer will fetch incremental data from a PostgreSQL table and write Avro serialized data into a Kafka topic. The consumers will deserialize this data and append it to separate 
JSON files.

## 2. Tools Required:
● Python 3.7 or later
● Confluent Kafka Python client
● PostgreSQL Database
● Apache Avro
● A suitable IDE for coding (e.g., PyCharm, Visual Studio Code)

## 3. Background:
You are working in a fictitious e-commerce company called **BuyOnline** which has a PostgreSQL database that stores product information such as product ID, name, category, price, 
and updated timestamp. The database gets updated frequently with new products and changes in product information. The company wants to build a real-time system to stream these updates 
incrementally to a downstream system for real-time analytics and business intelligence.
