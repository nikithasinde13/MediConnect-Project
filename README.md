🏥 MediConnect – Smart Healthcare Management System

<p align="center">
  <img src="https://img.shields.io/badge/Java-Spring%20Boot-success" />
  <img src="https://img.shields.io/badge/Frontend-Angular-red" />
  <img src="https://img.shields.io/badge/Security-JWT-blue" />
  <img src="https://img.shields.io/badge/Database-MySQL-orange" />
  <img src="https://img.shields.io/badge/Status-Incremental%20Project-brightgreen" />
</p><p align="center"><b>A secure, scalable, and role-based healthcare platform connecting Doctors and Patients.</b></p>
---

✨ Overview

MediConnect is a full-stack healthcare management system developed as part of the LTIMindtree – L&T Edutech Java Full Stack (Angular) Training Program.
The application enables seamless interaction between Doctors and Patients, ensuring secure authentication, appointment management, and medical data handling using JWT-based security.


---

👥 User Roles

🧑‍⚕️ Doctor

Secure login using JWT authentication

View assigned patients

Manage appointments

Update patient medical records


🧑‍🦱 Patient

Secure registration & login

Book appointments with doctors

View appointment history

Access personal medical details



---

🧩 Key Features

🔐 JWT-based Authentication & Authorization

🛡️ Role-Based Access Control (Doctor / Patient)

🌐 RESTful APIs using Spring Boot

⚡ Angular frontend with HTTP Interceptors

🗄️ Database persistence using JPA & Hibernate

🔄 CORS-enabled secure frontend-backend communication



---

🛠️ Tech Stack

Layer	Technology

Frontend	Angular, TypeScript, HTML, CSS
Backend	Java, Spring Boot, Spring Security
Security	JWT (HS512 Algorithm)
ORM	JPA, Hibernate
Database	MySQL
Tools	Git, GitHub, VS Code



---

🔐 Security Flow (JWT)

1. User logs in with credentials


2. Backend validates user details


3. JWT token generated using HS512 algorithm


4. Token sent to frontend


5. Angular attaches token to headers


6. JWT filter validates token for every request




---

🧱 Architecture

Angular UI
   ↓ HTTP Requests
Spring Boot Controllers
   ↓
Service Layer
   ↓
DAO / Repository Layer (JPA)
   ↓
MySQL Database


---

🚀 How to Run the Project

Backend

cd backend
mvn spring-boot:run

Frontend

cd frontend
npm install
ng serve


---

📂 Project Modules

Authentication & Authorization

Doctor Management

Patient Management

Appointment Scheduling

JWT Security Filter



---

🎓 Training & Evaluation

✅ Completed All 3 Milestones

📌 Capstone Project under LTIMindtree – L&T Edutech

🧪 Includes Mock Client Interview & Incremental Evaluation



---

📌 Future Enhancements

📅 Prescription module

🧾 Medical report uploads

📊 Admin dashboard

☁️ Cloud deployment



---

👨‍💻 Developed By

Sachin Sam Jacob
Java Full Stack Trainee (Angular)
LTIMindtree – L&T Edutech


---

⭐ If you like this project, don’t forget to give it a star on GitHub!
