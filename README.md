# SMS Project

A simple **House Management System** built with **PHP** and **MySQL**. It allows managing residents, houses, payments, and other related features.

---

## Features

* Manage residents and houses
* User login 
* Payment integration with **Stripe**
* Email sending using **PHPMailer**
* Admin and user roles
* Biling Management System

---

## Requirements

* **PHP 7.4+** (PHP 8 recommended)
* \*\*MySQL \*\*
* Web browser

---

## Installation (Step by Step)

1. **Download or Clone the Project**

   ```bash
   git clone https://github.com/gct-bsit-2021/Housing_Society_Management_system
   ```

   Or simply extract the `sms.zip` file into your server directory.

2. **Create Database**

   ```sql
   CREATE DATABASE housify CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
   ```

3. **Configure Database Connection**
   Open `sms/config.php` and update your MySQL credentials:

   ```php
   define('DB_HOST', 'localhost');
   define('DB_NAME', 'housify');
   define('DB_USER', 'root');
   define('DB_PASS', '');
   ```

4. **Import Database Schema**
   If you have the file `database.sql`:
   
6. **Run the Project**
 
   Then open your browser and visit: [http://localhost/sms]

## Example Usage

1. Start the PHP server.
2. Login a new user.
3. Email : sana@gmail.com Password: 1234
4. Login as Admin.
5. Email:213838bs@gmail.com  Password: 12345
6. Add houses and residents.
7. Test payment with Stripe (use test keys).
8. Check email notifications using PHPMailer.

---
