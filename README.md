<h1 align="center">🎓 Student Management System</h1>

<p align="center">
  A Full Stack Web Application to manage student records efficiently!
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

---

## 📌 About The Project

A full stack **Student Management System** built with **Java Spring Boot** backend and **HTML/CSS/JavaScript** frontend. This project demonstrates complete **CRUD operations** with a clean and responsive UI.

---

## ✨ Features

- ➕ **Add** new students
- 📋 **View** all students in a table
- ✏️ **Update** student details
- 🗑️ **Delete** students
- 🔍 **Search** students by ID
- 📱 **Responsive** UI design

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Java 17, Spring Boot 3.2 |
| **Database** | MySQL |
| **Frontend** | HTML5, CSS3, JavaScript |
| **ORM** | Spring Data JPA / Hibernate |
| **Build Tool** | Maven |
| **Version Control** | Git & GitHub |

---

## 📁 Project Structure
---

## 🚀 How To Run

### Prerequisites
- Java JDK 17+
- MySQL
- Maven

### Steps

**1. Clone the repository:**
```bash
git clone https://github.com/Jobigasanthirasekar/Student-Management-system.git
```

**2. Create MySQL database:**
```sql
CREATE DATABASE studentdb;
USE studentdb;
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL,
    age INT,
    department VARCHAR(100)
);
```

**3. Update application.properties:**
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/studentdb
spring.datasource.username=root
spring.datasource.password=your_password
```

**4. Run the project:**
```bash
mvn spring-boot:run
```

**5. Open browser:**
---

## 🌐 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | /api/students | Get all students |
| GET | /api/students/{id} | Get student by ID |
| POST | /api/students | Add new student |
| PUT | /api/students/{id} | Update student |
| DELETE | /api/students/{id} | Delete student |



 📸 Screenshots
<img width="1881" height="920" alt="image" src="https://github.com/user-attachments/assets/ef352d28-8d69-4fbf-844d-c6c2cb9e45f8" />



## 👨‍💻 Author

**Jobiga Santhirasekar**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Jobigasanthirasekar)

---

## ⭐ If you like this project — give it a star!
