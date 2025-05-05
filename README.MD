# 📘 Online Learning Platform - PHP & MySQL

An all-in-one web application for delivering online education, built with **PHP**, **MySQL**, **HTML/CSS**, and **Bootstrap**. This platform is designed for educational institutions, training centers, or individuals who want to offer structured online courses with user registration, course management, and assessments.

---

## 🧩 Project Overview

The **Online Learning Platform** allows administrators, teachers, and students to interact in a digital classroom environment. Teachers can create courses, upload materials, and assess students. Students can register, enroll in courses, view content, and take quizzes or tests.

---

## ✨ Features

### 👩‍🏫 For Instructor
- Create and manage courses
- Create lessons
- View enrolled students and  give cirtificate

### 👨‍🎓 For Students
- User registration and login
- Browse available courses
- Enroll in courses
- Access learning materials

### 🔐 Admin Panel
- Manage users (students/teachers)
- Approve or reject course content
- View system analytics
- Manage categories and course types

---

## ⚙️ Tech Stack

| Technology | Purpose                          |
|------------|----------------------------------|
| PHP        | Backend development              |
| MySQL      | Relational database              |
| HTML/CSS   | Frontend structure & styling     |
| Bootstrap  | Responsive design framework      |
| JavaScript | Interactivity and form handling  |
| XAMPP      | Local development environment    |

---

## 📂 Folder Structure

online-learning-platform/
│
├── admin/ # Admin dashboard and controls
├── user/ # student dashboard and course controls
├── courses/ # Course materials and views
├── includes/ # DB config, header, footer
├── assets/ # CSS, JS, images
├── index.php # Home/landing page
├── login.php # Login form
├── register.php # User registration
├── README.md # Project documentation
└── database.sql # SQL file to import tables

---

## 🚀 How to Set Up

### ✅ Prerequisites
- PHP 7.x or higher
- MySQL or MariaDB
- XAMPP/WAMP or any PHP server

### 🛠️ Steps

1. **Clone or Download Repository**
   ```bash
   git clone https://github.com/yourusername/online-learning-platform.git
Import the Database

Open phpMyAdmin

Create a database named online_learning

Import the file database.sql from the project

Update Configuration

Open includes/config.php

Set your DB credentials

$conn = new mysqli("localhost", "root", "", "online_learning");
Run the Application

Start Apache and MySQL in XAMPP

Go to: http://localhost/online-learning-platform/


You can also register as a new user (student or teacher).

📝 Future Improvements
Add payment gateway integration for paid courses

Implement video streaming for secure lectures

Live classroom integration with Zoom/Google Meet

Certificate generation upon course completion

Mobile app version using Flutter or React Native

🙋‍♂️ About the Developer
Name: Rashm Prava Mishra
GitHub: github.com/lopalopa
Email: lopalopa2007@gmail.com
LinkedIn: linkedin.com/in/rashmi-mishra-187734106/

📄 License
This project is licensed under the MIT License.
