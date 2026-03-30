# 🚀 JPMorgan Midas Core Simulation

## 🏦 Event-Driven Banking System

A backend system simulating real-time financial transaction processing using event-driven architecture, built as part of the JPMorgan Chase Software Engineering Virtual Experience (Forage).

---

## 💡 Overview

This project demonstrates how modern banking systems handle transactions asynchronously using Kafka-based messaging systems and Spring Boot services.

The system processes transactions in real time and provides REST APIs to query user balances.

---

## ⚙️ Architecture

Client → REST API → Kafka Producer → Kafka Topic → Consumer → Processing → Balance Service

---

## 🧠 Key Features

* Event-driven architecture using Apache Kafka
* Real-time transaction processing
* REST API for balance querying
* Modular backend structure
* Clean separation of concerns
* Embedded Kafka testing environment

---

## 🛠 Tech Stack

* Java 17
* Spring Boot
* Apache Kafka
* Maven
* REST APIs

---

## 📂 Project Structure

src/main/java/com/jpmc/midascore/

├── component/
│   └── TransactionListener.java

├── controller/
│   └── BalanceController.java

├── model/
│   └── Transaction.java

├── service/
│   └── BalanceService.java

├── config/
│   └── KafkaConfig.java

---

## 🚀 How to Run

git clone https://github.com/shrinidhinaik23/jpmorgan-midas-core-simulation.git

cd jpmorgan-midas-core-simulation

./mvnw clean install

./mvnw spring-boot:run

---

## 📡 API Endpoint

GET /balance?userId=1

Response:
{
"userId": 1,
"balance": 5000
}

---

## 📈 What I Implemented

* Kafka producer for streaming transactions
* Kafka consumer for asynchronous processing
* REST API for querying balances
* Transaction data modeling
* Integration between messaging system and backend services

---

## 🎯 Key Learnings

* Event-driven architecture
* Kafka-based asynchronous communication
* Backend system design
* Microservices fundamentals
* Real-time data processing

---

## ⚠️ Disclaimer

This project is built for educational purposes as part of a virtual experience program and does not represent production-level financial infrastructure.

---
