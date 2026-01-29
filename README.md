# Banking Portal

A full-stack Banking Portal application built with a modern frontend and a scalable backend architecture. The project simulates real-world banking operations with a strong focus on security, modularity, and maintainability.

---

## Project Overview

The Banking Portal provides essential banking functionalities such as user authentication, account management, and transaction handling. The system follows a clear separation of frontend and backend layers, enabling scalability, maintainability, and clean integration.

---

## Tech Stack

### Frontend
- Angular 18
- TypeScript
- Tailwind CSS
- Chart.js / ng2-charts

### Backend
- Java
- Spring Boot
- RESTful APIs
- JWT Authentication

### Database
- MySQL

### Tools & Others
- Git & GitHub
- Node.js (LTS)
- npm
- Maven

---

## Features

- Secure user authentication and authorization using JWT
- Account creation and management
- Transaction processing and transaction history
- Interactive dashboard with analytics and charts
- Responsive and modern user interface
- Secure and scalable backend APIs
- Clean, modular, and maintainable codebase

---

## Project Structure

```text
Banking-Portal/
│
├── BankingPortal-UI/
│   ├── src/
│   ├── angular.json
│   ├── package.json
│   └── README.md
│
├── BankingPortal-API/
│   ├── src/
│   ├── pom.xml
│   └── README.md
│
└── README.md
```

---

## ⚙️ Setup Instructions

1. Clone repository
```bash
git clone https://github.com/sourabhsingh88/Banking-Portal.git
cd Banking-Portal
```

2. Backend Setup (Spring Boot)
```bash
cd BankingPortal-API
# Configure MySQL in src/main/resources/application.properties (URL, username, password, etc.)
mvn spring-boot:run
```

Backend will run on:

http://localhost:8080

3. Frontend Setup (Angular)
```bash
cd BankingPortal-UI
npm install
ng serve
```

Frontend will run on:

http://localhost:4200

---

## 🔐 Authentication Flow

1. User logs in using credentials  
2. Backend issues a JWT token  
3. Token is stored on the client (e.g., localStorage/sessionStorage)  
4. Secured APIs validate JWT for every request

---

## 🚧 Project Status

- Core architecture completed
- Frontend and backend integrated
- Actively under development
- More features and optimizations planned

---

## 📈 Future Enhancements

- Role-based access control
- Admin dashboard
- Improved transaction analytics
- Dockerization
- CI/CD pipeline

---

## 👤 Author

Sourabh Singh  
Software Developer | Java | Spring Boot | Angular
