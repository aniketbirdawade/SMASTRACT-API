# SMASTRACT-API

SMASTRACT-API is a backend RESTful application built using **Spring Boot** that provides APIs for managing students, subjects, attendance, and user authentication.  
This project demonstrates practical backend development using Java and REST principles.

---

## Project Overview

SMASTRACT-API is designed as a **Student Management & Attendance Tracking System**.  
It exposes REST APIs that can be consumed by web or mobile applications.

---

## Tech Stack

- Java
- Spring Boot
- Maven
- REST API
- MySQL
- JPA / Hibernate

---

## Project Structure

```
SAMSTRACK_API/
├── src/main/java/com/tka/sams/api
│   ├── controller
│   ├── service
│   ├── dao
│   ├── entity
│   ├── model
│   └── SamsTrackApplication.java
│
├── src/main/resources
│   └── application.properties
│
├── pom.xml
└── mvnw
```

---

## Features

- User authentication APIs
- Student CRUD operations
- Subject management
- Attendance tracking
- Layered architecture

---

## How to Run

### Clone Repository
```bash
git clone https://github.com/aniketbirdawade/SMASTRACT-API.git
cd SMASTRACT-API
```

### Configure Database
Update `application.properties` with your MySQL details.

### Run Application
```bash
./mvnw spring-boot:run
```

or

```bash
mvn spring-boot:run
```

---

## Base URL

```
http://localhost:8080
```

---

## Author

Aniket Birdawade  
GitHub: https://github.com/aniketbirdawade

---

## License

This project is for learning and academic purposes.
