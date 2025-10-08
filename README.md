# E-commerce Project | Spring Boot & Kafka

This repository contains a sample e-commerce application built using **Spring Boot**, **Apache Kafka**, and **Maven**.  
It demonstrates a simple **order management system** designed with a **microservices architecture**.

---

## 🧩 Microservices Overview

### 🛒 Amazon Service
- Handles order creation via REST API
- Publishes order details to a Kafka topic

### 📦 Flipkart Service
- Listens to the Kafka topic for incoming orders
- Displays received orders via REST API

---

## 🚀 Key Features

- RESTful APIs for order creation and retrieval
- Asynchronous communication between services using **Apache Kafka**
- Follows producer-consumer design pattern
- Modular Maven multi-module project structure
- Easily extendable to support more platforms or services

---

## 🛠️ Tech Stack

- **Java 21**
- **Spring Boot 3.3.3**
- **Apache Kafka**
- **Maven**
- **REST APIs**

---
