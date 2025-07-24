# Product Service - Microservices Architecture

This is the Product Service of the `microservices-ecommerce` application.
4 of the following microservices forms a part of ecommerce project based on microservices architecture:
- product-service: https://github.com/Mayank135/ms-ecommerce-product-service
- order-service: https://github.com/Mayank135/ms-ecommerce-order-service
- inventory-service: https://github.com/Mayank135/ms-ecommerce-inventory-service
- api-gateway: https://github.com/Mayank135/ms-ecommerce-api-gateway

### Tech Stack:
- Java 17
- Spring Boot
- MongoDB
- Docker
- Testcontainers
- Maven

### Features:
- Create/Update/Delete products
- Fetch product list
- Integrated with MongoDB
- Can be run standalone or with Docker Compose

### Run Locally:

```bash
./mvnw spring-boot:run
