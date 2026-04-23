# SpringBootMicroservicesLearning
Spring Boot Microservices Learning
# FSD Backend

A Spring Boot microservice project for managing user oms. This backend service demonstrates RESTful API design, exception handling, and repository integration using Spring Data JPA.

---

## 🚀 Features
- REST API endpoints for user oms (`UserOrderController`)
- Exception handling with custom advice (`UserNotFoundException`, `UserNotFoundAdvice`)
- Data persistence using Spring Data JPA (`OrderRepository`)
- Organized package structure: controller, model, repository, exception
- Gradle build system

---

## 🛠 Tech Stack
- **Java 17+**
- **Spring Boot** (Web, Data JPA)
- **Gradle**
- **MySQL** (depending on configuration)
- **JUnit / Mockito** for testing
---

## ⚙️ Setup & Run

### Prerequisites
- Install **Java 17+**
- Install **Gradle** (or use included `gradlew` wrapper)
- Database (H2 in-memory by default, or configure MySQL/Postgres)

### Steps
```bash
# Clone the repository
git clone https://github.com/nagarajan21/SpringBootMicroservicesLearning.git
cd fsd-backend

# Build the project
./gradlew build

# Run the application
./gradlew bootRun

The service will start at:
http://localhost:8080
🔗 API Endpoints (for examples)
GET /oms → Fetch all user oms

GET /oms/{id} → Fetch order by ID
GET /oms/all → Fetch all orders

POST /oms → Create a new order

PUT /oms/{id} → Update an existing order

DELETE /oms/{id} → Delete an order


