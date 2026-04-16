# Digital Banking Platform

A full-stack digital banking application built with **Spring Boot** (backend) and **Angular** (frontend).


## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Quick Start](#quick-start)
- [API Documentation](#api-documentation)
- [Development Notes](#development-notes)
- [License](#license)


## Overview

This platform allows:
- Customer and account management
- Processing credit and debit transactions
- Viewing operation history
- Access via REST API & responsive Angular UI


## Project Structure

```
.
├── backend/   # Spring Boot REST API
└── frontend/  # Angular web application
```

- See dedicated READMEs in `backend/` and `frontend/` folders for further setup and info.



## Features

- Customer onboarding and searching
- Creation of current/savings bank accounts
- Credit/debit operations tracking
- Fully-documented RESTful API (Swagger/OpenAPI)
- Modern Angular web front end


## Tech Stack

**Backend:** Java 17, Spring Boot 3.x, Spring Data JPA, H2/MySQL, Springdoc Swagger  
**Frontend:** Angular 13, Bootstrap 5, RxJS, TypeScript


## Quick Start

### Prerequisites

- Java 17+
- Node.js (v14+ recommended) & npm
- Maven
- Angular CLI

### Backend

```sh
cd backend
./mvnw spring-boot:run
```

### Frontend

```sh
cd frontend
npm install
npm start
```

Frontend: [http://localhost:4200/](http://localhost:4200/)



## API Documentation

Swagger UI is available after starting the backend (see backend README for exact URL).


## Development Notes

- Backend is a layered Spring Boot REST API
- Frontend is a SPA consuming the REST API

