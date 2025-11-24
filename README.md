# Student Course Management & Analytics

## Overview
Lightweight Java-based web application to manage users, courses, enrollments, attendance and provide analytics for small colleges and instructors.

## Features
- User management (Admin / Instructor / Student)
- Course creation & enrollment management
- Attendance tracking and analytics dashboard
- Assignment submission and grade tracking
- CSV export of reports

## Technology Stack
- Java 17
- Spring Boot (Web, Security)
- Spring Data JPA
- Thymeleaf (server-rendered UI)
- H2 (development demo) / MySQL (production)
- Maven
- JUnit 5 + Mockito (unit tests)

## Quick Setup (development, H2 demo)
1. Clone the repository:
```
git clone https://github.com/sanatan24bsa10087-jpg/student-course-mgmt.git
cd student-course-mgmt
```

## DB Configuration
- For demo use H2 (default config in `application.yml`).
- To use MySQL, update `spring.datasource.*` in `application.yml` with your MySQL credentials.

## Tests
Run unit tests using Maven:
```
mvn test
```

## Project Structure (important)
```
src/main/java/com/student/scm
  ├─ Application.java
  ├─ config/
  ├─ controller/
  ├─ service/
  ├─ repository/
  ├─ model/
  └─ dto/
```

## Notes
- Passwords are hashed using BCrypt.
- Use `application.yml` to switch between H2 and MySQL.

