# SpringDockerDB

A containerized backend application built with **Spring Boot**, **MySQL**, and **Docker**, designed to demonstrate scalable, production-ready service development using RESTful APIs and structured inter-database communication via **gRPC**.

---

## Features

- RESTful API built using **Spring Boot**
- Integrated **MySQL** database for persistent storage
- **Docker** container for consistent deployment environments
- **gRPC** integration to enable efficient and structured inter-database or inter-service communication
- Modular architecture for easy extension or migration

---

## Tech Stack

| Component     | Technology        |
|---------------|-------------------|
| Backend       | Spring Boot (Java)|
| Database      | MySQL             |
| Containerization | Docker         |
| Communication | RESTful, gRPC        |
| Build Tool    | Maven             |

---

## Getting Started

### Prerequisites

* Docker
* JDK 17+
* Maven

---

### Run with Docker

1. Clone the repository

```bash
git clone https://github.com/adityapatel1010/SpringDockerDB.git
cd SpringDockerDB
```

2. Build and start services

```bash
docker-compose up --build
```

3. Access API at:

```
http://localhost:8080/api/
```

---

### Run Locally (Without Docker)

1. Create a local MySQL database

2. Update your `application.properties` with local DB credentials

3. Run the app

```bash
mvn spring-boot:run
```

---

## gRPC Integration

* gRPC used for high-performance, strongly-typed communication between services or databases
* Useful in distributed systems and microservice architecture for schema enforcement

---

## Skills Demonstrated

* Backend development with **Spring Boot**
* API design and versioning with REST
* Database integration with **MySQL**
* Docker-based service orchestration
* Introduction to **gRPC** for inter-service communication

---

Let me know if you'd like to expand the gRPC section with actual `.proto` file samples or integrate Swagger for API documentation!
```
