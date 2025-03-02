# GMAO Application - End of Studies Project

## Overview
The **GMAO Application** is a web-based **Computerized Maintenance Management System (CMMS)** developed as part of an end-of-studies project. It provides tools for managing maintenance tasks, tracking interventions, handling reclamations, and overseeing equipment, rooms, and preventive maintenance operations.

## Features
- **User Authentication & Role Management** (Admin, User, Intervenant, etc.)
- **Equipment & Room Management**
- **Intervention & Reclamation Handling**
- **Preventive & Corrective Maintenance Tracking**
- **Work Order (OT) Management**
- **PDF Report Generation**
- **Dashboard & Statistics**

## Technologies Used
### Backend:
- **Spring Boot** (Java)
- **Spring Security & JWT Authentication**
- **JPA/Hibernate**
- **MySQL Database**
- **Maven**
- **Thymeleaf for PDF Reports**

### Frontend:
- **Angular**
- **TypeScript**
- **SCSS**
- **Material Design**

## Project Structure
```
├── Backend
│   ├── src/main/java/com/example/gmaoapp/
│   │   ├── controllers/    # API Controllers
│   │   ├── models/         # Data Models
│   │   ├── repository/     # Database Repositories
│   │   ├── services/       # Business Logic
│   │   ├── security/       # Authentication & Authorization
│   ├── resources/          # Configuration files
│   ├── pom.xml             # Maven Dependencies
│
├── Frontend
│   ├── src/app/
│   │   ├── core/           # Core App Features
│   │   ├── dashboard/      # Dashboard Components
│   │   ├── auth/           # Authentication System
│   │   ├── services/       # API Services
│   ├── package.json        # Node Dependencies
│   ├── angular.json        # Angular Config
```

## Installation & Setup
### Backend Setup
1. Install Java (JDK 11 or later) and Maven.
2. Clone the repository.
3. Configure the `application.properties` file in `src/main/resources/`.
4. Build and run the backend:
   ```sh
   mvn spring-boot:run
   ```

### Frontend Setup
1. Install Node.js and Angular CLI.
2. Navigate to the `Frontend` directory.
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the Angular application:
   ```sh
   ng serve --open
   ```
