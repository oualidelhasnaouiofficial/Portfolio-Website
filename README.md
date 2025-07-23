<h1 align="center">🚀 Portfolio Website</h1>

<p align="center">
  <strong>
    A professional, multilingual, and fully customizable personal website built with Laravel and Bootstrap 5.
  </strong><br/>
  Showcasing your skills, experience, and projects in the most elegant digital format possible.
</p>

<!-- Main Hero Image (for both web & print) -->
<p align="center">
  <img src="https://github.com/oualidelhasnaouiofficial/44/blob/main/OUALID%20EL%20HASNAOUI%20(3).png"
       alt="Hero Screen"
       width="85%"
       style="border-radius: 16px;" />
</p>

---

## 🔗 Live Demo

🌍 Deployed at: [**oualidelhasnaoui.site**](https://oualidelhasnaoui.site)

---
<p align="center">
  <img src="https://github.com/oualidelhasnaouiofficial/44/blob/main/OUALID%20EL%20HASNAOUI%20(1).png"
       width="100%" style="border-radius: 12px;" />
  
</p>


<p align="center">
  <a href="https://oualidelhasnaoui.site" target="_blank">
    <img src="https://img.shields.io/badge/🌐_Visit Website-000000?style=for-the-badge" />
  </a>
  <a href="https://oualidelhasnaoui.site/services" target="_blank">
    <img src="https://img.shields.io/badge/🛠️_Services-6c63ff?style=for-the-badge" />
  </a>
  <a href="https://oualidelhasnaoui.site/projects" target="_blank">
    <img src="https://img.shields.io/badge/📁_All Projects-28a745?style=for-the-badge" />
  </a>
  <a href="https://oualidelhasnaoui.site/storage/phto-pr/2025-cv-professionnel-oualid-elh.pdf" target="_blank">
    <img src="https://img.shields.io/badge/📄_View CV-blue?style=for-the-badge" />
  </a>
  <a href="https://oualidelhasnaoui.site/admin/login" target="_blank">
    <img src="https://img.shields.io/badge/🔐_Admin Dashboard-dd2c00?style=for-the-badge" />
  </a>
</p>

## 🧭 Overview

> A fully responsive, CMS-powered portfolio website tailored for developers, freelancers, and digital creatives.

- ✨ Pixel-perfect interface  
- 🌍 Multilingual & RTL built-in  
- 🧠 AI content-ready  
- 🔐 Admin dashboard
- 📱 Mobile-first layout  
- 📈 SEO & Analytics ready

---
## 🖼️ Screenshots (Web + Print Ready)

<p align="center">
    <img src="https://github.com/oualidelhasnaouiofficial/44/blob/main/Screenshot%202025-07-23%20064301.png"
       width="100%" style="border-radius: 12px;" />
  <img src="https://github.com/oualidelhasnaouiofficial/44/blob/main/Screenshot%202025-07-23%20080438.png"
       width="100%" style="border-radius: 12px;" />
  <img src="https://github.com/oualidelhasnaouiofficial/44/blob/main/Screenshot%202025-07-23%20080817.png"
       width="100%" style="border-radius: 12px;" />
  <img src="https://github.com/oualidelhasnaouiofficial/44/blob/main/Screenshot%202025-07-23%20075826.png"
       width="100%" style="border-radius: 12px;" />
</p>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-10-red?style=for-the-badge&logo=laravel" />
  <img src="https://img.shields.io/badge/PHP-8.2-blue?style=for-the-badge&logo=php" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql" />
  <img src="https://img.shields.io/badge/Bootstrap-5-purple?style=for-the-badge&logo=bootstrap" />
</p>

---



## 📂 Folder Structure

Here's a high-level overview of the key folders and files:

portfolio-website/
├── app/ # Core app logic (models, services, providers)
├── bootstrap/ # Framework bootstrap files
├── config/ # All project configuration files
├── database/ # Migrations and seeders
│ ├── migrations/ # Database table definitions
│ └── seeders/ # Initial dummy/admin data
├── public/ # Publicly accessible files (index.php, uploads, assets)
│ ├── themes/ # Compiled frontend assets
│ └── uploads/ # Media and file uploads
├── resources/ # Views, language files, and raw assets
│ ├── views/ # Blade templates
│ ├── lang/ # Translation files
│ └── assets/ # SCSS, JS, images before compilation
├── routes/ # Route definitions
│ ├── web.php # Web-facing routes
│ └── api.php # API routes
├── storage/ # Compiled views, cache, logs, etc.
├── tests/ # PHPUnit tests
├── .env # Environment-specific variables
└── artisan # Laravel CLI entry point

# 🚀 Deploying Laravel  on Hostinger

Welcome! 👋  
This guide walks you through deploying your **Laravel-based portfolio website  **Hostinger**, step by step.

---

## ✅ Requirements

- ✔️ Active domain (e.g., `oualidelhasnaoui.site`)
- ✔️ Hostinger hosting plan (Shared or Premium)
- ✔️ Laravel project 
- ✔️ MySQL database credentials

---

## 📦 1. Prepare Your Project

1. On your local machine:
   - Delete the `vendor/` folder to reduce size.
   - Compress the project as a `.zip` file.

2. In Hostinger:
   - Go to **File Manager > public_html**
   - Delete any default files like `index.html`.
   - Upload your `.zip` and **extract** it into `public_html`.

---

## 🗃️ 2. Create the Database

1. In the Hostinger dashboard:
   - Navigate to **MySQL Databases**.
   - Create a new **database**, **username**, and **password**.
   - Note down all credentials.

---

## ⚙️ 3. Configure `.env` File

1. Locate the `.env` file (or copy `.env.example` → rename to `.env`)
2. Update the database and app config:

```env
APP_NAME="Portfolio"
APP_URL=https://oualidelhasnaoui.site

DB_CONNECTION=mysql
DB_HOST=localhost
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_db_username
DB_PASSWORD=your_db_password


