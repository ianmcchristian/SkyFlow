# SkyFlow Lite

SkyFlow Lite is a "Digital Twin" project that simulates an airport traffic control system using a modern microservices architecture.

## Technology Stack

- **Backend:** Java 17, Spring Boot
- **Frontend:** React
- **Messaging:** Apache Kafka
- **Database:** MongoDB
- **Infrastructure:** Docker, Docker Compose
- **Security:** Keycloak (IAM), HashiCorp Vault (Secrets), Trivy (Scanning)

## Getting Started

### Prerequisites

- Docker & Docker Compose
- Java 17
- Node.js

### Running the Infrastructure

```bash
docker compose up -d
```

This will start the following services:
- **Kafka:** Port 9094
- **Zookeeper:** Port 2181
- **MongoDB:** Port 27017
- **Keycloak:** Port 8080
- **Vault:** Port 8200
