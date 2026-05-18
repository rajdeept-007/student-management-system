# student-management-system
A **containerized full-stack Student Management System** developed using **Spring Boot, MySQL, Docker, and Docker Compose**.

This project demonstrates practical implementation of **DevOps concepts** such as:

- Containerization
- Service Orchestration
- Networking
- Multi-container Deployment

The application allows management of **student records, examinations, marks, and report generation** through a web-based interface.

---

# 🚀 Project Features

## 📚 Student Management

- Add, update, and delete student records
- Manage student details and status
- Search and filter students
- Pagination support

---

## 📝 Academic Management

- Manage exams and marks
- Generate results and report cards
- Grade calculation system

---

## 📤 Export Features

- Export data as **PDF** and **CSV**
- Printable student ID cards

---

## ⚙️ DevOps Features

- Multi-container Docker setup
- Docker Compose orchestration
- Isolated frontend, backend, and database services
- Persistent MySQL storage using Docker volumes

---

# 🛠️ Technologies Used

## 🎨 Frontend

- HTML
- CSS
- JavaScript
- Nginx

---

## 🔧 Backend

- Java 11
- Spring Boot
- REST API
- Hibernate
- Maven

---

## 🗄️ Database

- MySQL 8

---

## 🚢 DevOps Tools

- Docker
- Docker Compose
- phpMyAdmin

---

# ⚙️ How to Run the Project

## Step 1: Clone Repository
git clone https://github.com/YOUR_USERNAME/student-management-system.git
cd student-management-system

## ⚙️ Step 2: Start Docker Containers
docker-compose up --build

# 🌐 Access the Application

| Service | URL | Credentials |
|----------|------|-------------|
| Frontend UI | http://localhost:3000 | - |
| Backend API | http://localhost:8080/api/students | - |
| PHPMyAdmin | http://localhost:8081 | root / root123 |

---

# 🛑 Stop the Application

# Stop all containers
docker-compose down
# Stop and delete volumes (reset database)
docker-compose down -v

Developed as a DevOps & Full-Stack practice project using Docker and Spring Boot.
