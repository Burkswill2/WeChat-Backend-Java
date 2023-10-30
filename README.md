# ModuloChat Backend - Java

This repo contains the Java backend implementation for ModuloChat.

## Overview

The Java backend provides core chat capabilities and messaging infrastructure using Spring Boot.

Key features:

- Real-time messaging with Spring WebSockets
- Persistent storage with Spring Data JPA
- REST APIs for chat resources
- Horizontal scaling with Spring Cloud

## Getting Started

Requirements: 

- Java 11+
- Maven

```
# Clone the repo
git clone https://github.com/modulochat/backend-java

# Build jar
mvn clean package 

# Run
java -jar target/modulochat-backend-1.0.jar
```

The server will start on port 8080.

## Architecture

Built with:

- Spring Boot for application framework
- Spring Data JPA for database abstraction
- Hibernate as JPA provider
- PostgreSQL for production database
- Redis for messaging

See [Architecture Documentation](https://github.com/modulochat/details/docs/Architecture.md) for more details.

## Testing

Integration tests using Spring Boot Test. Unit tests with JUnit and Mockito.

```
mvn test
```
