# springboot-kafka-mssql-microservices
End-to-end Kafka producer and consumer implementation using Spring Boot, with MS SQL Server integration.

This project demonstrates a simple microservices architecture using:
- Java
- Spring Boot
- Apache Kafka
- MS SQL Server
- Maven

## Architecture
- employee-producer: REST API that publishes Employee events to Kafka
- employee-consumer: Kafka consumer that persists Employee data to MS SQL

## Tech Stack
- Java 17
- Spring Boot
- Spring Kafka
- Spring Data JPA
- MS SQL Server
- Apache Kafka

## Kafka Flow
REST API → Kafka Producer → Kafka Topic → Kafka Consumer → MS SQL

## How to Run
1. Start Kafka on localhost
2. Start SQL Server on localhost
3. Run employee-consumer
4. Run employee-producer
5. Call POST /employees API
