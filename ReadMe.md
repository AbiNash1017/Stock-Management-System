# 📦 Stock Management System | PHP | MySQL | OOP

![PHP](https://img.shields.io/badge/PHP-8.0.7-blue?logo=php)
![MySQL](https://img.shields.io/badge/Database-MySQL-blue?logo=mysql)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap%20%2B%20AdminLTE-purple)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen)

> A web-based inventory and stock tracking system built with PHP (OOP) & MySQL. Designed for small to mid-sized businesses to manage purchases, receiving, back orders, returns, and sales records with ease.
---

### 🧑‍💻 Author

**Abinash Das**  
📅 **Date**: Nov 2023  
📩 **Contact**: abinash.das.dev@gmail.com  
🔗 [GitHub - AbiNash1017](https://github.com/AbiNash1017)

---
## 🚀 Features at a Glance

- 🔐 Secure Login / Logout
- 📦 Stock Management (Add, View, Edit, Delete)
- 🛒 Purchase Orders & Receiving
- 📉 Back Orders (Auto-generated if items are missing)
- 🔁 Return Management (Auto-deducts from stock)
- 💰 Sales Record Tracking
- 👥 Role-Based Access: Admin & Staff
- 🖨️ Printable records for PO, Receiving, BO, Returns, and Sales
- 🧾 CRUD for Items, Suppliers, Users, and System Settings

---

## 💻 Tech Stack

- **Backend**: PHP (OOP), MySQL
- **Frontend**: HTML, CSS, Bootstrap, AdminLTE
- **Enhancements**: JavaScript, jQuery, AJAX
- **Local Server**: XAMPP v3.3.0 (PHP 8.0.7)

---

## 🧩 Installation

```bash
git clone https://github.com/AbiNash1017/Stock-Management-System.git
```
Open **XAMPP / WAMP** and start **Apache** & **MySQL**.

---

## 🔧 Setup Instructions (Continued)

1. **Copy the project folder**  
   Move the cloned/extracted project folder to:
   - `htdocs/` (if using XAMPP)
   - `www/` (if using WAMP)

2. **Database Configuration**
   - Open [phpMyAdmin](http://localhost/phpmyadmin)
   - Create a **new database** named: `sms_db`
   - Import the SQL dump:
     - Navigate to the `database/` folder inside the project.
     - Select and import the `sms_db.sql` file.

3. **Access the Application**
   - Open your browser and go to:
     ```
     http://localhost/sms/
     ```

4. **Default Admin Access**
    - **Username**: `admin`
    - **Password**: `admin123`

---

## 📋 User Roles

- **System Admin**
- Full access to all modules: CRUD operations, reporting, stock flow tracking, and system configuration.

- **Staff**
- Limited access focused on daily stock operations like adding sales, receiving items, etc.

---

## 📂 Project Structure


---

## ✅ Future Improvements (Suggestions)

- 📊 Dashboard Analytics with charts
- 📦 Low Stock Alert System
- 📧 Email Notifications
- 📱 Mobile Responsive Enhancements
- 🧾 Invoice/PDF Export Feature



## 📝 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

> 🛠️ Built with simplicity, modular design, and business practicality in mind.
> Contribute, fork, or enhance it as needed!

