# SBMS Service Registry

A centralized Service Registry built using Spring Boot and Netflix Eureka for the Smart Banking Management System (SBMS) microservices architecture.

## 📌 Project Overview

The `SBMS-service-registry` project acts as a Eureka Server where all microservices register themselves and discover other services dynamically. It helps in maintaining communication between multiple microservices without hardcoding service URLs.

This project is mainly used in a distributed microservices environment.

---

## 🚀 Technologies Used

* Java 17
* Spring Boot
* Spring Cloud Netflix Eureka Server
* Maven
* REST APIs
* Microservices Architecture

---

## 📂 Project Structure

```text
SBMS-service-registry
│── src/main/java
│── src/main/resources
│    └── application.yml
│── pom.xml
│── README.md
```

---

## ⚙️ Features

* Eureka Server Configuration
* Dynamic Service Registration
* Service Discovery
* Centralized Microservice Management
* Easy Integration with Other SBMS Services

---

## 🛠️ Prerequisites

Before running this project, ensure you have:

* Java 17 or above
* Maven installed
* IDE (IntelliJ IDEA / Eclipse / VS Code)

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/SBMS-service-registry.git
```

### Step 2: Navigate to the Project

```bash
cd SBMS-service-registry
```

### Step 3: Build the Project

```bash
mvn clean install
```

### Step 4: Run the Application

```bash
mvn spring-boot:run
```

---

## 🌐 Eureka Dashboard

After starting the application, open:

```text
http://localhost:8761/
```

You can view all registered microservices in the Eureka Dashboard.

---

## 📄 Sample application.yml

```yaml
server:
  port: 8761

spring:
  application:
    name: SBMS-SERVICE-REGISTRY


eureka:
  client:
    register-with-eureka: false
    fetch-registry: false
```


---

## 👩‍💻 Author

Shanthi

Java Developer | Spring Boot | Microservices

