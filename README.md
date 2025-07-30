# 📝 Exam Portal Backend (Microservices Architecture)
Tech Stack: Backend Language: Java 17+  Frameworks: Spring Boot, Spring Cloud, Spring Security  Microservices: RESTful Microservices Architecture  Service Discovery: Eureka Server  API Gateway: Spring Cloud Gateway  Authentication: JWT (JSON Web Tokens)  Database: Oracle  ORM: Spring Data JPA. Kafka / RabbitMQ (for asynchronous processing) 



A scalable, secure, and modular backend system for an Online Exam Portal built using **Java**, **Spring Boot**, and **Microservices Architecture**.

---

## 🔧 Tech Stack

- **Language:** Java 17+
- **Frameworks:** Spring Boot, Spring Cloud, Spring Security
- **Microservices:** RESTful APIs
- **Authentication:** JWT (JSON Web Tokens)
- **Service Discovery:** Eureka Server
- **API Gateway:** Spring Cloud Gateway
- **Database:** MySQL / PostgreSQL
- **ORM:** Spring Data JPA
- **Documentation:** Swagger / OpenAPI
- **Containerization:** Docker (optional)
- **Build Tool:** Maven

---

## 📦 Microservices Overview

| Service              | Description                                  |
|----------------------|----------------------------------------------|
| **User Service**     | Handles user registration, login, and roles      |
| **Exam Service**     | Manages exam creation and metadata           |
| **Question Service** | CRUD operations for exam questions           |
| **Result Service**   | Evaluates and stores exam submissions        |
| **API Gateway**      | Entry point for routing and security         |
| **Eureka Server**    | Service registry for service discovery       |
| **Notification Service (optional)** | Email/SMS alerts for exam events |

---

## 🔐 Security

- JWT Authentication & Authorization
- Role-based access control (Admin, Examiner, Student)
- Passwords encrypted using BCrypt
- Token validation and refresh

---

## ⚙️ How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/exam-portal-backend.git
   cd exam-portal-backend
   cd eureka-server
   mvn spring-boot:run
   cd api-gateway
   mvn spring-boot:run
   mvn spring-boot:run ```

2. exam-portal-backend/
    │
    ├── api-gateway/
    ├── eureka-server/
    ├── user-service/
    ├── exam-service/
    ├── question-service/
    ├── result-service/
    └── notification-service/ (optional)



