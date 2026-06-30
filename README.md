<<<<<<< HEAD
# ApexPlanet — 45-Day PHP & MySQL Internship

![PHP](https://img.shields.io/badge/PHP-8.2-blue?logo=php)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?logo=mysql)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple?logo=bootstrap)
![PDO](https://img.shields.io/badge/Database-PDO-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A complete, portfolio-grade blog application built progressively across 5 internship tasks.
Covers environment setup, full CRUD with authentication, search & pagination, security hardening,
and a polished final project.

---

## Live Demo
> Run locally — see setup instructions below.

---

## Task Progress

| # | Task | Duration | Topics | Status |
|---|------|----------|--------|--------|
| 1 | Development Environment | 3 days | XAMPP, VS Code, Git, GitHub | ✅ |
| 2 | Basic CRUD + Auth | 10 days | MySQL, PDO, Sessions, password_hash | ✅ |
| 3 | Search + Pagination + UI | 10 days | LIKE queries, LIMIT/OFFSET, Bootstrap | ✅ |
| 4 | Security Enhancements | 10 days | CSRF, prepared stmts, roles, lockout | ✅ |
| 5 | Final Integrated Project | 12 days | All above combined + audit log | ✅ |

---

## Features

- **Authentication** — Register, login, logout with bcrypt password hashing
- **CRUD** — Create, read, update, delete blog posts
- **Search** — Search posts by title or content with keyword highlighting
- **Pagination** — Configurable posts-per-page with navigation
- **User Roles** — admin / editor / user with role-based access control
- **CSRF Protection** — Token in every form, verified on submission
- **Brute-force Protection** — Account lockout after 5 failed login attempts
- **Audit Log** — Every login, post action logged with IP & user agent
- **Admin Dashboard** — Manage users, change roles, view activity

---

## Project Structure

```
apexplanet-internship/
├── admin/
│   └── dashboard.php        ← Admin: user management, activity log
├── assets/
│   ├── css/style.css        ← Custom theme (CSS variables + Bootstrap overrides)
│   └── js/main.js           ← Validation, strength meter, toggle password
├── auth/
│   ├── login.php            ← Login with brute-force lockout
│   ├── logout.php           ← Secure session destroy
│   └── register.php         ← Registration with password policy
├── config/
│   └── database.php         ← PDO singleton connection
├── database/
│   └── schema.sql           ← Full DB schema + seed data
├── includes/
│   ├── auth_helpers.php     ← requireLogin, requireRole, CSRF, e(), logActivity
│   ├── header.php           ← Navbar + flash messages
│   └── footer.php           ← Scripts + closing tags
├── posts/
│   ├── index.php            ← List with search & pagination
│   ├── view.php             ← Single post
│   ├── create.php           ← New post form
│   ├── edit.php             ← Edit form
│   └── delete.php           ← Confirm & delete
└── index.php                ← Homepage
=======
# 🚀 Task 3 - Advanced Features Implementation

![PHP](https://img.shields.io/badge/PHP-8.x-blue?style=for-the-badge\&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge\&logo=mysql)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-purple?style=for-the-badge\&logo=bootstrap)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?style=for-the-badge\&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge\&logo=github)

## 📌 Project Overview

This repository contains **Task 3 - Advanced Features Implementation** developed as part of the **ApexPlanet Software Pvt. Ltd. Web Development Internship Program**.

This project enhances the CRUD Blog Application from Task 2 by implementing advanced features such as **Search Functionality**, **Pagination**, and an improved **Responsive User Interface** using Bootstrap.

---

## 🎯 Objectives

* Enhance the CRUD application with advanced features.
* Implement search functionality for blog posts.
* Add pagination to improve data navigation.
* Improve the overall user experience and interface design.
* Build a responsive and user-friendly application.

---

## 🛠️ Technologies Used

| Technology  | Purpose                   |
| ----------- | ------------------------- |
| PHP         | Server-Side Scripting     |
| MySQL       | Database Management       |
| Bootstrap 5 | Responsive UI Design      |
| HTML5       | Structure                 |
| CSS3        | Styling                   |
| JavaScript  | Client-Side Functionality |
| Git         | Version Control           |
| GitHub      | Repository Hosting        |

---

## ✨ Features Implemented

### 🔍 Search Functionality

* Search blog posts by title.
* Search blog posts by content.
* Dynamic search results display.
* User-friendly search interface.

### 📄 Pagination

* Displays a limited number of posts per page.
* Previous and Next navigation buttons.
* Page number navigation.
* Better performance for large datasets.

### 🎨 User Interface Improvements

* Responsive Bootstrap design.
* Modern navigation bar.
* Improved forms and buttons.
* Attractive post cards.
* Enhanced user experience across devices.

### 🔐 Existing Features

* User Registration
* User Login & Logout
* Password Hashing
* Session Management
* Create Posts
* Read Posts
* Update Posts
* Delete Posts

---

## 📂 Project Structure

```text
apexplanet-internship/
│
├── index.php
├── README.md
│
├── admin/
│   └── dashboard.php
│
├── auth/
│   ├── login.php
│   ├── logout.php
│   └── register.php
│
├── config/
│   └── database.php
│
├── database/
│   └── schema.sql
│
├── includes/
│   ├── auth_helpers.php
│   ├── header.php
│   └── footer.php
│
├── posts/
│   ├── create.php
│   ├── delete.php
│   ├── edit.php
│   ├── index.php
│   └── view.php
│
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
│
└── screenshots/
>>>>>>> a5e5a517fee125be4089cc9c049a6ed182ff922a
```

---

<<<<<<< HEAD
## Quick Start

### Prerequisites
- XAMPP (Apache + MySQL) — https://www.apachefriends.org
- PHP 8.2+
- Git

### Setup

```bash
# 1. Clone into XAMPP web root
git clone https://github.com/YOUR_USERNAME/apexplanet-internship.git C:/xampp/htdocs/apexplanet-internship

# 2. Start XAMPP → Apache + MySQL

# 3. Import database
#    Open http://localhost/phpmyadmin
#    Create database "blog" → Import → database/schema.sql

# 4. Open in browser
http://localhost/apexplanet-internship
```

### Demo Accounts (from seed data)

| Role   | Username  | Password   |
|--------|-----------|------------|
| Admin  | admin     | password   |
| Editor | editor    | password   |
| User   | john_doe  | password   |

> **Change passwords immediately in production!**

---

## Security Measures (Task 4)

| Threat | Mitigation |
|--------|-----------|
| SQL Injection | PDO prepared statements on every query |
| XSS | `htmlspecialchars()` / `e()` on all output |
| CSRF | Token in every form, `hash_equals()` verification |
| Brute Force | 5-attempt lockout for 15 minutes |
| Session Fixation | `session_regenerate_id(true)` on login |
| Password Storage | `password_hash()` bcrypt, never plaintext |
| Directory Listing | `Options -Indexes` in .htaccess |
| Privilege Escalation | `requireRole()` guard on admin pages |
| Information Leakage | Generic error messages; errors logged server-side |

---

## Git Commit Log Summary

```
feat: task1 — project structure, config, header/footer, CSS, JS
feat: task2 — schema.sql, CRUD posts, auth (register/login/logout)
feat: task3 — search with highlight, pagination, UI polish
feat: task4 — CSRF, brute-force lockout, roles, activity_log, admin
feat: task5 — final integration, README, cleanup
=======
## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/apexplanet-internship.git
```

### Navigate to Project

```bash
cd apexplanet-internship
```

### Database Setup

Create a database named:

```sql
CREATE DATABASE blog;
```

Import:

```text
database/schema.sql
```

### Configure Database

Update database credentials in:

```php
config/database.php
```

### Run Application

Place project inside:

```text
xampp/htdocs/
```

Start:

* Apache Server
* MySQL Server

Open:

```text
http://localhost/apexplanet-internship/
>>>>>>> a5e5a517fee125be4089cc9c049a6ed182ff922a
```

---

<<<<<<< HEAD
## Interview Questions (Quick Reference)

1. **What is PDO and why use it over mysqli?** — PDO is a DB abstraction layer; supports prepared statements preventing SQL injection; works with 12+ databases; better OOP error handling.
2. **How does CSRF protection work?** — Server generates a random token stored in session; token embedded in every form; on POST, submitted token compared with `hash_equals()` (timing-safe); mismatch = 403.
3. **Why bcrypt for passwords?** — Deliberately slow (cost factor); each hash unique (salted); `password_verify()` is timing-attack safe; `password_hash()` future-proofs with PASSWORD_DEFAULT.
4. **What is session fixation and how did you prevent it?** — Attacker sets a known session ID before login; we call `session_regenerate_id(true)` on successful login, issuing a new ID.
5. **Explain pagination SQL.** — `LIMIT $perPage OFFSET (($page-1)*$perPage)`; total pages = `ceil(total_rows / perPage)`; always bind LIMIT/OFFSET as `PDO::PARAM_INT`.

---

## Author

**Your Name** — ApexPlanet Internship  
📧 your@email.com | 🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | 🐙 [GitHub](https://github.com/yourusername)
=======
## 📸 Output

Successfully Implemented:

✅ Search Functionality

✅ Pagination

✅ Responsive Bootstrap UI

✅ Authentication System

✅ CRUD Operations

✅ Session Management

✅ MySQL Integration

✅ User-Friendly Design

---

## 📚 Learning Outcomes

* Advanced PHP Development
* Database Query Optimization
* Search Implementation
* Pagination Techniques
* Responsive Web Design
* Bootstrap Integration
* User Experience Enhancement
* Full CRUD Application Development

---

## 👨‍💻 Author

**T. Nithya Santhoshini**

B.Tech Student | Web Development Intern

GitHub: https://github.com/Nithya2910

LinkedIn: https://www.linkedin.com/in/nithya-santhoshini-thangellapelli-a62b9634a/

---

## 📄 Internship

**ApexPlanet Software Pvt. Ltd.**

Web Development Internship (PHP & MySQL)

Task-3: Advanced Features Implementation
>>>>>>> a5e5a517fee125be4089cc9c049a6ed182ff922a
