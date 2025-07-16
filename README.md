# 🔐 Spring Boot Security Practice

This project is a complete practice implementation of **Spring Boot Security**, covering real-world authentication & authorization techniques including:

- ✅ JWT (JSON Web Token) authentication
- ✅ Role-based access control
- ✅ Custom login & logout endpoints
- ✅ Secure password hashing with BCrypt
- ✅ CSRF protection (optional toggle)
- ✅ In-memory and database-based users
- ✅ Exception handling for unauthorized access
- ✅ Basic CORS setup for frontend communication
### Prerequisites:
- Java 17+
- Maven or Gradle
- IntelliJ / VS Code
- Postman (for testing APIs)

### To Run:
```bash
./mvnw spring-boot:run

#🔑 API Security Flow
Login Endpoint → /api/auth/login

JWT Token Issued

Protected Endpoints require Bearer token in headers

Role-based access for endpoints like /admin/**, /user/**

📦 Technologies Used
Spring Boot

Spring Security

JWT

Maven / Gradle

H2 / MySQL (for persistence)

Lombok (for boilerplate removal)



