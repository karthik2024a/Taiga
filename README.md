# 🚀 Agile Sprint Management System

A full-stack Agile Project Management web application built using **Spring Boot (Backend)** and **React (Frontend)**.

This system enables teams to manage projects, sprints, issues, and time logs efficiently using Agile methodology principles.

---

## 🏗️ Tech Stack

### 🔹 Frontend
- React.js
- Axios
- CSS (Custom Styling)
- React Hooks

### 🔹 Backend
- Spring Boot
- Spring Security (JWT Authentication)
- JPA / Hibernate
- RESTful APIs

### 🔹 Database
- MySQL

### 🔹 Tools Used
- Maven
- Postman (API Testing)
- Git & GitHub

---

## 📂 Project Structure

```
Agile-Sprint-Management-System/
│
├── Frontend-Agile-frontend/
├── backend/
├── Database/
└── README.md
```

---

## ✨ Key Features

### 🔐 Authentication
- User Registration
- Login with JWT Authentication
- Secure REST APIs using Spring Security

---

### 📁 Project Management
- Create Project
- Update Project
- Delete Project
- View All Projects

---

### 🏃 Sprint Management
- Create Sprint
- Assign Sprint to Project
- Update Sprint Status

---

### 🐞 Issue Tracking
- Create Issues
- Assign Issues to Sprint
- Track Issue Status

---

### ⏱️ Time Logging System
- Add Time Log
- Update Time Log
- Delete Time Log
- View logs by:
  - Day
  - Week
  - Month
  - Year
- Automatic total hours calculation

---

### 📊 Reporting
- Sprint summary
- Time tracking overview
- Productivity tracking

---

## ⚙️ Installation & Setup

---

### 🔹 Backend Setup (Spring Boot)

1️⃣ Clone the repository:

```bash
git clone https://github.com/Karthik2024a/Agile-Sprint-Management-System.git
cd backend
```

2️⃣ Configure MySQL in `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/agile_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

3️⃣ Run the backend:

```bash
mvn clean install
mvn spring-boot:run
```

Backend runs at:
```
http://localhost:8080
```

---

---

### 🔹 Backend API Testing

All backend APIs were tested using **Postman**, including:

- Authentication APIs  
- Project CRUD APIs  
- Sprint APIs  
- Issue APIs  
- Task (Kanban Board) APIs  
- Time Log APIs  

---

## 🔐 API Endpoints Overview

### 🔑 Authentication
```
POST   /api/auth/register
POST   /api/auth/login
```

---

### 📁 Projects
```
GET    /api/projects
POST   /api/projects
PUT    /api/projects/{id}
DELETE /api/projects/{id}
```

---

### 🏃 Sprints
```
GET    /api/sprints
POST   /api/sprints
PUT    /api/sprints/{id}
DELETE /api/sprints/{id}
```

---

### 🐞 Issues
```
GET    /api/issues
POST   /api/issues
PUT    /api/issues/{id}
DELETE /api/issues/{id}
```

---

### 🗂️ Tasks (Kanban Board)
```
GET    /api/tasks
POST   /api/tasks
PUT    /api/tasks/{id}
DELETE /api/tasks/{id}
```

Features:
- Drag and drop task status updates
- Move tasks between columns (To Do, In Progress, Done)
- Track task progress visually

---

### ⏱️ Time Logs
```
GET    /api/timelogs/my
POST   /api/timelogs/{issueId}
PUT    /api/timelogs/{id}
DELETE /api/timelogs/{id}
```

---
## 🚀 Deployment (Optional)

### Backend
- Railway / Render / AWS

### Frontend
- Vercel / Netlify

---

## 🧠 Learning Outcomes

- Full-stack development using React & Spring Boot
- JWT authentication implementation
- REST API design
- CRUD operations
- Agile workflow modeling
- Date filtering logic (Day/Week/Month/Year)
- Backend API testing using Postman
- Real-world project structure

---

## 👨‍💻 Author

**Karthik**

GitHub: https://github.com/Karthik2024a  

---

## 📜 License

This project is created for educational and portfolio purposes.
