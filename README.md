# Student–Teacher Management System

A web-based dashboard system for managing student and teacher profiles, academic data, analytics, and login authentication.  
Built with HTML, Tailwind CSS, JavaScript and Chart.js, using `localStorage` for demo persistence.

---

## 👤 Student Information
**Name:** Devanshu Gupta  
**College ID:** 2024KUEC2027 
**Batch:** C1

---

## 📝 Project Description

The **Student–Teacher Management System** is a responsive multi-page website designed for educational institutions.  
It provides role-based access (student/teacher), data visualization of student metrics, and tools for teachers to add or update student records.

Key capabilities:
- Multi-page UI (Home, Student, Teacher, About, Contact, Login)
- Student data CRUD (teacher adds/updates; students view)
- Charts (department distribution, gender split, CGPA trends) using Chart.js
- All data stored locally (localStorage) for demo purposes
- Responsive layout styled with Tailwind CSS

---

## 🎯 Key Features

### 🔹 Home Page
- School introduction and image slider/gallery  
- About, Facilities, Reviews  
- Navbar with logo and login/profile icon  
- Footer

### 🔹 Login System
- Client-side authentication (demo)
- Redirects based on role:
  - Students → Student Dashboard
  - Teachers → Teacher Dashboard

### 🔹 Student Dashboard
- Student details table (auto-updated from teacher actions)  
- Charts:
  - Department Bar Chart
  - Gender Pie Chart
  - CGPA Line Chart
- Charts update when teacher adds/changes data

### 🔹 Teacher Dashboard
- Form to add new student records (ID, name, dept, year, gender, attendance, CGPA)  
- Student table with the same styling as student dashboard  
- Data saved to `localStorage` so student page reads it automatically

### 🔹 About Page
- Vision, mission, why choose us, gallery

### 🔹 Contact Page
- Contact form, phone, email, correct Google Maps embed

---

## 🔐 Demo Login Credentials

> These are sample/demo accounts used by the front-end JS authentication.

**Students**
- `student1` / `password123`  
- `student2` / `pass456`

**Teachers**
- `teacher1` / `teach123`  
- `teacher2` / `teach456`

---

## 🛠 Technologies Used

- **HTML5** — page structure  
- **Tailwind CSS** — styling & responsiveness  
- **JavaScript** — logic, authentication, storage  
- **Chart.js** — charts and visualizations  
- **localStorage** — demo persistent storage

---

## 📁 Deployment Link (Mandatory)
Live Project Link :
https://dev-gupta248.github.io/BrightFuture_School/

---
