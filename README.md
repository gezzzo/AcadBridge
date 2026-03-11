# AcadBridge

A web-based academic advising and student service management system built with **PHP** and **MySQL**.  
The project provides separate interfaces for **students**, **supervisors**, and **administrators**.

## Overview

System1 is designed to simplify communication between students and academic supervisors, while also supporting common academic service workflows such as:

- Student registration and login
- Supervisor login
- Course/material management
- Academic requests (add / drop)
- Frequently asked questions
- Student-supervisor chat
- Admin dashboard for managing students, supervisors, materials, and questions

## Features

### Student
- Register a new account
- Log in
- View homepage
- View academic supervisor
- Browse materials/courses
- Submit academic requests
- View FAQs
- Chat with supervisor

### Supervisor
- Log in
- View student-related data
- Respond to messages
- Follow up on requests

### Admin
- Manage students
- Manage supervisors
- Manage materials
- Manage FAQ content
- Monitor chats and records

## Project Structure

```bash
system1/
├── admin/                  # Admin dashboard
├── assets/                 # CSS, JS, images
├── dashboard/              # Dashboard-related files
├── index.php               # Landing page
├── home.php                # Home page after login
├── loginstudent.php        # Student login
├── loginsupervisor.php     # Supervisor login
├── registerstudent.php     # Student registration
├── materials.php           # Materials page
├── orders.php              # Requests/orders page
├── professors.php          # Supervisors page
├── Qn.php                  # FAQ page
├── chat.php                # Chat page
├── logout.php              # Logout
└── database.sql            # Database dump

```
## License

This project is licensed under the MIT License.
