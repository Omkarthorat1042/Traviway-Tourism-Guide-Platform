# Travyway: A Microservices-based Tourism Management System  

![Java](https://img.shields.io/badge/Java-17-blue)  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-brightgreen)  
![React](https://img.shields.io/badge/Frontend-React-blue)  
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-lightblue)  
![License: MIT](https://img.shields.io/badge/License-MIT-yellow)  
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange)  
![GitHub stars](https://img.shields.io/github/stars/Omkarthorat1042/Traviway-Tourism-Guide-Platform?style=social)  
![GitHub forks](https://img.shields.io/github/forks/Omkarthorat1042/Traviway-Tourism-Guide-Platform?style=social)  
![GitHub issues](https://img.shields.io/github/issues/Omkarthorat1042/Traviway-Tourism-Guide-Platform)  

---

## 📌 Overview  
**Travyway** is a modern **tourism management system** built with a **microservices-based full-stack architecture**.  
It provides an interactive platform for travelers to explore destinations, plan trips, and access rich travel content.  

The system is designed for **scalability, modularity, and resilience**, with dedicated services for content management, authentication, notifications, and user interactions.  

---

## 🏗️ Architecture  

The project follows **Microservices Architecture**, where each service handles one business capability independently.  

- **Eureka Server** – Service discovery registry  
- **API Gateway** – Single entry point for routing, security, and CORS  
- **Dedicated Microservices** – Each focusing on features like authentication, content, users, and notifications  

---

## 💻 Technology Stack  

### Frontend  
- React + Vite  
- React Router DOM  
- Axios  
- Tailwind CSS  

### Backend (Microservices)  
- Java 17 + Spring Boot  
- Spring Cloud (Eureka, Gateway, Feign Client)  
- Spring Data JPA  
- Spring Security + JWT (JJWT)  
- Spring Boot Starter Mail  

### Database  
- PostgreSQL  

---

## 🔧 Microservices Breakdown  

| Service                | Port | Description |
|-------------------------|------|-------------|
| **eureka-server**       | 8761 | Service registry for microservices |
| **api-gateway**         | 8080 | Routes all frontend requests to backend services |
| **content-service**     | 8081 | Manages tourism content (cities, places, categories) |
| **user-service**        | 8082 | Handles user profiles, reviews, wishlists, and blogs |
| **auth-service**        | 8083 | Manages user registration, login, JWT authentication |
| **notification-service**| 8084 | Handles email notifications (e.g., contact form) |

---

## ✨ Key Features  

### 🌍 User Features  
- Dynamic homepage with carousel & featured destinations  
- Explore **cities, attractions, and places to visit**  
- **AI Trip Planner** (Gemini API) → generates personalized itineraries  
- Functional **contact form** that sends email to admin  

### 🔐 Backend Features  
- **JWT Authentication & Authorization**  
- **Role-based access control** (`USER`, `ADMIN`)  
- **Inter-service communication** with Feign + Eureka  
- Secure API Gateway routing  

---

## 🚀 Getting Started  

### ✅ Prerequisites  
- JDK 17+  
- Maven  
- PostgreSQL  
- Node.js + npm  

### ⚙️ Database Setup  
1. Start PostgreSQL  
2. Create database: `travyway`  
3. Run script: `newsqlfile.sql` (creates tables + dummy data)  


