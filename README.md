# 🎓 Student Management System (Spring Boot)

A simple **Student Management System** developed using **Spring Boot**, **Spring Data JPA**, and **H2/MySQL** to perform CRUD operations on students.

---

## 🚀 Features

- Add new students
- View all students
- Update student information
- Delete student records
- RESTful API endpoints
- Input validation
- In-memory database (H2) or MySQL support

---

## 🛠️ Tech Stack

- **Backend:** Spring Boot, Spring Web, Spring Data JPA
- **Database:** H2 (for development), MySQL (optional for production)
- **Tools:** Maven,  Postman (for testing)
- **Java Version:** 17+

---

## 🧾 API Endpoints

| Method | Endpoint            | Description          |
|--------|---------------------|----------------------|
| GET    | `/api/students`     | Get all students     |
| GET    | `/api/students/{id}`| Get student by ID    |
| POST   | `/api/students`     | Add new student      |
| PUT    | `/api/students/{id}`| Update student       |
| DELETE | `/api/students/{id}`| Delete student       |
