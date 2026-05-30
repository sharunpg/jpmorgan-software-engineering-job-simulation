# JPMorgan Chase Software Engineering Job Simulation

This repository contains my implementation of the **JPMorgan Chase Software Engineering Job Simulation** hosted on **Forage**.

## Overview

The project focuses on building **Midas Core**, a backend financial transaction processing system capable of:

- Processing financial transactions
- Kafka-based message handling
- Database persistence using H2
- REST API integration
- User balance retrieval

The project was completed as part of the **JPMorgan Chase Software Engineering Job Simulation**.

## Technologies Used

- Java 17
- Spring Boot
- Apache Kafka
- H2 Database
- Spring Data JPA
- REST API
- Maven

## Features Implemented

### Task 1 – Project Setup
- Configured Java 17 environment
- Set up Maven and Spring Boot project
- Added required dependencies
- Configured application properties

### Task 2 – Kafka Integration
- Implemented Kafka Listener
- Consumed transaction messages
- Deserialized transaction data

### Task 3 – H2 Database Integration
- Integrated H2 in-memory database
- Validated transactions
- Updated sender and recipient balances
- Persisted transaction records using JPA

### Task 4 – REST API Integration
- Integrated REST endpoints for backend services
- Processed transaction-related requests

### Task 5 – REST API Controller
- Built `/balance` endpoint
- Returned user balance using JSON response
- Implemented GET request handling

## Project Structure

````md
## 📂 Project Structure

```text
midas-core
├── .mvn/
│   └── wrapper/
│
├── src/
│   ├── main/
│   │   ├── java/com/jpmc/midascore/
│   │   │   ├── component/
│   │   │   │   ├── KafkaConfig.java
│   │   │   │   └── KafkaTransactionListener.java
│   │   │   │
│   │   │   ├── controller/
│   │   │   │   └── BalanceController.java
│   │   │   │
│   │   │   ├── entity/
│   │   │   │   ├── UserRecord.java
│   │   │   │   └── TransactionRecord.java
│   │   │   │
│   │   │   ├── foundation/
│   │   │   │   ├── Balance.java
│   │   │   │   └── Transaction.java
│   │   │   │
│   │   │   ├── repository/
│   │   │   │   ├── TransactionRepository.java
│   │   │   │   └── UserRepository.java
│   │   │   │
│   │   │   └── MidasCoreApplication.java
│   │   │
│   │   └── resources/
│   │       └── application.yml
│   │
│   └── test/
│       └── java/com/jpmc/midascore/
│           ├── TaskOneTests.java
│           ├── TaskTwoTests.java
│           ├── TaskThreeTests.java
│           ├── TaskFourTests.java
│           └── TaskFiveTests.java
│
├── target/
├── pom.xml
├── mvnw
├── mvnw.cmd
├── README.md
└── .gitignore
````

```
```


## Learning Outcomes

Through this simulation, I gained practical exposure to:

- Enterprise backend development
- Event-driven architecture using Kafka
- Database integration using Spring Data JPA
- RESTful API development
- Financial transaction processing systems

## Certificate

Successfully completed the **JPMorgan Chase Software Engineering Job Simulation** on Forage in May 2026. :contentReference[oaicite:1]{index=1}

## Author

**Sharun Prakash Gurramkonda**

- GitHub: https://github.com/sharunpg
- LinkedIn: https://www.linkedin.com/in/sharun-prakash-gurramkonda-27459b25b/
