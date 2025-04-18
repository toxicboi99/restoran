# 🍽️ Restaurant Website

A modern, responsive restaurant website using **HTML, CSS, Bootstrap, JavaScript, PHP**, and **MySQL**. This project allows users to view the menu, book reservations, send messages, and browse a beautiful UI with interactive components.

---

## 📌 Table of Contents

1. [Project Overview](#project-overview)  
2. [Requirements](#requirements)  
3. [Tools Used](#tools-used)  
4. [Frontend Details](#frontend)  
5. [Backend Details](#backend)  
6. [Database Structure](#database-structure)  
7. [Folder Structure](#folder-structure)  
8. [Screenshots](#screenshots)  
9. [Setup Instructions](#setup-instructions)  
10. [Future Improvements](#future-improvements)  
11. [Contact Info](#contact-info)

---

## 📖 Project Overview

This is a fully functional restaurant website built with a responsive layout and connected to a backend database using PHP and MySQL. The goal is to simulate a real-world application for restaurants to manage menus, reservations, and contact queries.

---

## ✅ Requirements

- A web server (e.g. XAMPP, WAMP, MAMP)
- PHP 7.x or higher
- MySQL or MariaDB
- Modern web browser (Chrome, Firefox, etc.)

---

## 🧰 Tools Used

| Tool          | Purpose                                |
|---------------|----------------------------------------|
| VS Code       | Code Editor                            |
| XAMPP/WAMP    | Localhost server for PHP & MySQL       |
| phpMyAdmin    | GUI for database management             |
| GitHub        | Version control and hosting            |
| Google Fonts  | Custom web fonts                       |
| Font Awesome  | Icons for UI                           |

---

## 🎨 Frontend

Built using:

- **HTML5** for page structure
- **CSS3** for custom styling
- **Bootstrap 5** for responsive layout
- **JavaScript** for interactivity (form validation, sliders, etc.)
- **Font Awesome** for icons

### Key Pages:
- `index.html` – Homepage with intro, highlights
- `menu.php` – Dynamically loaded menu from DB
- `contact.php` – Contact form
- `reserve.php` – Table reservation form
- `about.html` – About the restaurant
- `gallery.html` – Photo gallery

---

## 🔧 Backend

Developed using:

- **PHP** for server-side logic
- **MySQL** for database management
- **phpMyAdmin** for DB handling
- **AJAX** (optional) for dynamic content (optional feature)

### Backend Functionality:

- Handles form submissions
- Stores reservation data
- Fetches menu items dynamically from DB
- Sends contact form data (optionally to email or DB)

---

## 🗄️ Database Structure

### Database Name: `restoran_db`

#### 🧾 `menu`
| Field       | Type         |
|-------------|--------------|
| id          | INT (PK)     |
| name        | VARCHAR(100) |
| description | TEXT         |
| price       | DECIMAL(10,2)|
| category    | VARCHAR(50)  |
| image       | VARCHAR(255) |

#### 🧾 `reservations`
| Field   | Type         |
|---------|--------------|
| id      | INT (PK)     |
| name    | VARCHAR(100) |
| email   | VARCHAR(100) |
| phone   | VARCHAR(15)  |
| date    | DATE         |
| time    | TIME         |
| people  | INT          |

#### 🧾 `testimonials`
| Field   | Type         |
|---------|--------------|
| id      | INT (PK)     |
| name    | VARCHAR(100) |
| comment | TEXT         |
| rating  | INT          |

---

## 📂 Folder Structure

