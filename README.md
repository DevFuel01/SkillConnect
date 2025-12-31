# SkillConnect
A skill-based networking platform connecting students and innovators with mentors and collaborators.

SkillConnect 🚀

A skill-based networking platform connecting students and innovators with mentors and collaborators.

📌 Overview

SkillConnect is a web-based platform designed to bridge the gap between students, innovators, and mentors. It enables users to discover collaborators, seek guidance, and share knowledge through skill-based matching, messaging, and community discussions.

This project was built as part of the “2025 Your Last Project with QODER” hackathon, with a strong focus on real-world impact over hype.

🎯 Problem Statement

Many students and young innovators struggle to find:

Mentors to guide their growth

Collaborators with complementary skills

Communities to share ideas and projects

Traditional networking is slow, fragmented, and often inaccessible.

💡 Solution

SkillConnect provides a centralized platform where users can:

Create skill-based profiles

Get matched with mentors or collaborators

Communicate via private messaging

Participate in discussion forums

All powered by a simple, scalable web architecture.

✨ Key Features
🔐 Authentication & Security

User registration and login

Secure password hashing

Session-based authentication

Role-based access (Admin / User)

👤 User Profiles

Editable profiles with:

Name

Email

Skills

Interests

Project goals

🤝 Skill-Based Matching

PHP-powered recommendation system

Matches users based on shared skills and interests

Suggestions displayed on user dashboard

💬 Communication

Private one-to-one messaging

Timestamped conversations

AJAX-powered dynamic message loading

🧠 Discussion Forum

Create discussion topics

Post and reply to threads

Community-driven knowledge sharing

🧑‍💼 Admin Dashboard

View and manage users

Monitor forum activity

Basic moderation capabilities

🛠️ Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	PHP
Database	MySQL
Server	Apache (XAMPP)
Version Control	Git & GitHub
🗂️ Project Structure
SkillConnect/
├── public/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── css/
│   └── js/
├── backend/
│   ├── config.php
│   ├── auth.php
│   ├── match.php
│   ├── forum.php
│   └── messages.php
├── database/
│   └── database.sql
├── docs/
│   └── screenshots/
├── README.md
└── .gitignore

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/YOUR_USERNAME/SkillConnect.git
cd SkillConnect

2️⃣ Set Up Database

Open phpMyAdmin

Create a database (e.g. skillconnect_db)

Import database/database.sql

3️⃣ Configure Backend

Edit backend/config.php:

$host = "localhost";
$user = "root";
$password = "";
$database = "skillconnect_db";

4️⃣ Run the Project

Start Apache & MySQL in XAMPP

Open browser and visit:

http://localhost/SkillConnect/public/

🧪 Demo

Live Demo: (Add link if deployed)

Demo Video: (2–3 minutes recommended)

🌍 Impact

SkillConnect empowers students and innovators by:

Making mentorship accessible

Encouraging collaboration

Supporting idea-to-project growth

Building a scalable innovation community

🔮 Future Improvements

AI-powered advanced matching

Project posting & recruitment

Notification system

Profile verification badges

Analytics dashboard

🏁 Hackathon Info

Hackathon: 2025 Your Last Project with QODER

Requirement: New project built using QODER

Category: Web Application / Social Impact

📜 License

This project is for educational and hackathon purposes.
