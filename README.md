# Core Banking & Digital Wallet Management System

Enterprise-level backend system simulating real banking operations, built using **Spring Boot**, **MySQL**, and **RESTful APIs**.
The project demonstrates modern backend architecture, financial transaction handling, and scalable service-layer design.

## Key Features

* Customer management system
* Bank account creation and management
* Digital wallet integration
* Deposit and withdrawal operations
* Account-to-account money transfers
* Transaction ledger tracking
* REST API architecture for service communication

## Technology Stack

* **Backend:** Spring Boot (Java)
* **Database:** MySQL
* **ORM:** Spring Data JPA / Hibernate
* **API Testing:** Postman
* **Build Tool:** Maven
* **Version Control:** Git & GitHub

## System Modules

* Customer Management
* Account Management
* Wallet System
* Transaction Processing
* Financial Ledger

## Example API Endpoints

```
POST   /customers
GET    /customers
POST   /accounts
POST   /accounts/deposit
POST   /accounts/withdraw
POST   /transactions/transfer
POST   /wallets
GET    /wallets/{walletNumber}
```

## Run It

1. Create the database:

   ```sql
   CREATE DATABASE corebanking;
   ```

2. Set your MySQL credentials as environment variables (read by `application.properties`):

   ```bash
   export DB_USERNAME=root
   export DB_PASSWORD=your_mysql_password
   ```

3. Start the app (needs Maven installed):

   ```bash
   cd corebanking-system
   mvn spring-boot:run
   ```

The API runs at `http://localhost:8082`. There is no authentication layer; this is a learning project, not a production banking system.

## Architecture

Layered architecture following enterprise backend standards:

```
Controller → Service → Repository → Database
```

## Learning Objective

This project demonstrates how modern **fintech backend systems** handle customer accounts, wallet services, and secure financial transactions using Spring Boot.

---

**Author:** Jisan
Software Engineer | Data Science | Student
