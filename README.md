# Spring Security JWT Authentication

## Overview
This project implements JWT-based authentication and authorization using Spring Boot 3.4.3 and Spring Security. It provides user registration, login, and protected API endpoints that require authentication.

## Features
- User registration and login
- JWT-based authentication and authorization
- Role-based access control (RBAC)
- Secure API endpoints
- Spring Boot 3.4.3 & Spring Security

## Technologies Used
- **Spring Boot** 3.4.3
- **Spring Security**
- **JSON Web Tokens (JWT)**
- **Java** 21
- **Maven**
- **MySQL** (configurable)

## Configure the application
Update application.properties (or application.yml) to configure database and JWT properties.

## API Endpoints
- POST /api/auth/register – Register a new user
- POST /api/auth/login – Authenticate and receive a JWT token
- GET /api/user/profile – Access a protected endpoint (requires authentication)

## Author
Chaima Jerbi
