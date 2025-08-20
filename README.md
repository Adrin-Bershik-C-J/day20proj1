# 🐞 Bug Tracker API (Spring Boot + JWT Security)

A **Bug Tracking System** built with **Spring Boot**, **Spring Security (JWT)**, and **JPA**.  
This project provides secure authentication, role-based access control, and CRUD operations for managing software bugs.

---

## 🚀 Features

- 🔐 **JWT Authentication** with role-based access:
  - `ADMIN` → Create, Update, Delete bugs
  - `DEVELOPER` → View & Update bugs
  - `USER` → View bugs
- 📄 **REST APIs** for bug management
- 🔎 **Filtering & Search** bugs by status, assignee, project
- 📑 **Pagination support**
- 🛡️ **Spring Security** with custom JWT filter
- 🗄️ **H2 Database** (in-memory) for quick testing
- 🧩 **DTO + MapStruct** for clean response mapping

---

## 📂 Project Structure

```
Directory structure:
└── adrin-bershik-c-j-day20proj1/
    ├── README.md
    ├── mvnw
    ├── mvnw.cmd
    ├── pom.xml
    ├── src/
    │   ├── main/
    │   │   ├── java/
    │   │   │   └── com/
    │   │   │       └── example/
    │   │   │           └── day14proj1/
    │   │   │               ├── Day14proj1Application.java
    │   │   │               ├── config/
    │   │   │               │   └── SecurityConfig.java
    │   │   │               ├── controller/
    │   │   │               │   ├── AuthController.java
    │   │   │               │   └── BugController.java
    │   │   │               ├── dto/
    │   │   │               │   ├── BugResponseDTO.java
    │   │   │               │   ├── UserRequestDTO.java
    │   │   │               │   └── UserResponseDTO.java
    │   │   │               ├── entity/
    │   │   │               │   ├── Bug.java
    │   │   │               │   └── User.java
    │   │   │               ├── mapper/
    │   │   │               │   ├── BugMapper.java
    │   │   │               │   └── UserMapper.java
    │   │   │               ├── repository/
    │   │   │               │   ├── BugRepository.java
    │   │   │               │   └── UserRepository.java
    │   │   │               └── service/
    │   │   │                   ├── BugService.java
    │   │   │                   ├── JwtAuthFilter.java
    │   │   │                   ├── JwtService.java
    │   │   │                   └── UserService.java
    │   │   └── resources/
    │   │       └── application.properties
    │   └── test/
    │       └── java/
    │           └── com/
    │               └── example/
    │                   └── day14proj1/
    │                       └── Day14proj1ApplicationTests.java
    └── .mvn/
        └── wrapper/
            └── maven-wrapper.properties
```

---

## ⚙️ Tech Stack

- **Java 17**
- **Spring Boot 3**
- **Spring Security + JWT**
- **Spring Data JPA**
- **H2 Database** (default)
- **Maven**

---

## ▶️ Running the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Adrin-Bershik-C-J/day20proj1.git
cd day20proj1
```
