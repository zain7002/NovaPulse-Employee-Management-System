# 🚀 NovaPulse – Employee Management System

![Java](https://img.shields.io/badge/Java-17+-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![MySQL](https://img.shields.io/badge/MySQL-8.x-blue)
![Maven](https://img.shields.io/badge/Maven-Build-red)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange)

## 📌 About the Project

**NovaPulse** is a full-stack Employee Management System developed to manage employee information through a professional web application.

The project uses **Spring Boot** for the backend, **MySQL** for database management, and **HTML, CSS, and JavaScript** for the frontend.

The backend provides REST APIs for employee management, while the frontend communicates with these APIs to display and manage employee records.

---

## ✨ Features

- 👤 Add new employees
- 📋 View all employees
- 🔍 Search employees by department
- 🔎 Search employees by first name
- 📧 Search employee by email
- ✏️ Update employee details
- 🗑️ Delete employees
- 📱 Store employee phone numbers
- ✅ Input validation
- ⚠️ Exception handling
- 🔗 REST API integration
- 🗄️ MySQL database integration
- 🧪 Postman API testing

---

## 🛠️ Technologies Used

### Backend

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- Jakarta Validation
- REST API

### Database

- MySQL
- MySQL Workbench

### Frontend

- HTML5
- CSS3
- JavaScript

### Testing

- Postman

### Development Tools

- IntelliJ IDEA
- VS Code
- Git
- GitHub

---

# 🏗️ Project Architecture

```text
                    ┌──────────────────────┐
                    │       Frontend       │
                    │   HTML / CSS / JS    │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      REST API        │
                    │ EmployeeController   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    Service Layer     │
                    │   EmployeeService    │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Repository Layer   │
                    │ EmployeeRepository   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       MySQL           │
                    │employee_management_db │
                    └──────────────────────┘
