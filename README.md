# Digital Banking Platform

A full-stack digital banking application built with **Spring Boot** for the backend and **Angular** for the frontend.  
The application provides a REST API for managing customers, bank accounts, and transactions, with a modern web interface for interacting with the banking system.

## Project Structure

- `backend/` — Spring Boot REST API
- `frontend/` — Angular web application

## Features

- Customer management
- Bank account creation
- Current and savings account support
- Credit and debit transactions
- Account operation tracking
- RESTful API documentation with Swagger/OpenAPI
- Frontend built with Angular and Bootstrap

## Tech Stack

### Backend
- Java 17
- Spring Boot 3.4.x
- Spring Data JPA
- Spring Web
- Spring Security OAuth2 Resource Server
- H2 Database
- MySQL Connector
- Lombok
- Springdoc OpenAPI / Swagger UI

### Frontend
- Angular 13
- TypeScript
- Bootstrap 5
- Bootstrap Icons
- RxJS

## Getting Started

### Prerequisites
- Java 17+
- Node.js and npm
- Angular CLI
- Maven

### Backend
```bash
cd backend
./mvnw spring-boot:run
