# 🚗 DriveEase – Car Rental Management System

## Overview

DriveEase is a full-stack Car Rental Management System that enables users to browse vehicles, manage bookings, and list rental cars through an intuitive web interface.

The application follows a modern enterprise architecture using Spring Boot, React, and MySQL, demonstrating secure authentication, RESTful API development, database integration, and scalable backend design.

This project highlights full-stack development skills, clean architecture principles, and real-world business workflow implementation.

---

## Features

* User Authentication and Authorization
* Vehicle Listing Management
* Browse Available Cars
* Car Search and Filtering
* Rental Booking Management
* User Dashboard
* Booking Tracking
* Responsive Modern UI
* REST API Integration
* Secure Spring Security Configuration
* MySQL Database Persistence
* Hibernate/JPA ORM Integration
* Multi-Step Vehicle Listing Workflow

---

## Tech Stack

### Frontend

* React.js
* JavaScript (ES6+)
* HTML5
* CSS3

### Backend

* Java
* Spring Boot
* Spring MVC
* Spring Security
* Spring Data JPA

### Database

* MySQL

### ORM

* Hibernate

### Build & Development Tools

* Maven
* Git
* GitHub
* VS Code
* MySQL Workbench

---

## Architecture

```text
DriveEase
│
├── Frontend (React)
│
├── Backend (Spring Boot)
│   ├── Controllers
│   ├── Services
│   ├── Repositories
│   └── Models
│
└── MySQL Database
```

### Workflow

1. Users interact with the React frontend.
2. Frontend sends requests to Spring Boot APIs.
3. Controllers handle incoming requests.
4. Services process business logic.
5. Repositories communicate with MySQL.
6. Responses are returned to the frontend.

---

## Installation

### Prerequisites

* Java 21+
* Maven
* Node.js
* MySQL
* Git

### Clone Repository

```bash
git clone https://github.com/your-username/DriveEase.git
cd DriveEase
```

### Backend Configuration

Configure your database credentials inside:

```properties
src/main/resources/application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD
```

### Run Backend

```bash
mvn spring-boot:run
```

Backend will run on:

```text
http://localhost:8081
```

### Run Frontend

```bash
cd my-app
npm install
npm run dev
```

Frontend will run on:

```text
http://localhost:5173
```

---

## Usage

### User Features

* Browse available vehicles
* Search and filter cars
* Create bookings
* Manage reservations
* View dashboard information

### Vehicle Owner Features

* List rental vehicles
* Manage vehicle details
* Configure availability and pricing

---

## Future Enhancements

* JWT Authentication
* Role-Based Access Control
* Payment Gateway Integration
* Email Notifications
* Booking Cancellation Workflow
* Vehicle Availability Tracking
* Admin Dashboard
* Docker Deployment
* Cloud Deployment (AWS/Azure)
* Analytics & Reporting

---

## Challenges Solved

* Implemented layered Spring Boot architecture
* Integrated React frontend with Spring Boot backend
* Configured Hibernate ORM with MySQL
* Designed scalable repository-service-controller pattern
* Implemented secure authentication workflow
* Managed entity relationships and persistence

---

## Learning Outcomes

* Full-Stack Application Development
* Spring Boot REST APIs
* React Frontend Development
* Database Design and Integration
* Hibernate & JPA
* Authentication and Security
* MVC Architecture
* Software Engineering Best Practices
* Version Control with Git & GitHub

---

## Topics

```text
spring-boot
java
react
mysql
hibernate
jpa
spring-security
maven
rest-api
full-stack
car-rental
web-application
backend-development
frontend-development
software-engineering
```

---

## Author

**Varshitha Nagothu**

GitHub: https://github.com/NagothuVarshitha
