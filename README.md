# 🍽️ Apna Restaurant Management System

A web-based Restaurant Management System developed using **PHP**, **MySQL (MariaDB)**, **HTML**, **CSS**, **JavaScript**, and **Bootstrap**. This project allows users to view restaurant information, browse the menu, register, log in, submit reviews, and contact the restaurant.

---

# 📌 Features

- User Registration
- User Login
- Restaurant Home Page
- Food Menu
- Image Gallery
- Customer Reviews
- Contact Us Page
- Admin Panel
- MySQL Database Integration

---

# 🛠️ Technologies Used

- PHP
- HTML5
- CSS3
- JavaScript
- Bootstrap
- MySQL / MariaDB
- XAMPP

---

# 💻 Software Requirements

Before running this project, make sure the following software is installed:

- Windows 10/11
- XAMPP (Apache + MariaDB/MySQL + PHP)
- Web Browser (Chrome, Edge, Firefox)
- Visual Studio Code (Optional)

---

# 📥 Install XAMPP

Download the latest version of XAMPP from the official website:

https://www.apachefriends.org/

Install XAMPP in the default location:

```
C:\xampp
```

---

# 📂 Project Setup

## Step 1

Extract the project ZIP file.

## Step 2

Copy the project folder:

```
Apna_restaurent
```

Paste it into:

```
C:\xampp\htdocs\
```

Final project location:

```
C:\xampp\htdocs\Apna_restaurent
```

---

# ▶️ Start XAMPP

Open **XAMPP Control Panel**.

Start the following services:

- Apache
- MySQL (MariaDB)

Both services should display **Running**.

---

# 🗄️ Database Setup

Open Command Prompt and run:

```
C:\xampp\mysql\bin\mysql.exe -u root
```

Create the database:

```sql
CREATE DATABASE maher;
EXIT;
```

Import the SQL file:

```
C:\xampp\mysql\bin\mysql.exe -u root maher < "C:\xampp\htdocs\Apna_restaurent\database\maher.sql"
```

---

# 🌐 Run the Project

Open your browser and visit:

```
http://localhost/Apna_restaurent
```

---

# 🔐 Admin Panel

If available, open:

```
http://localhost/Apna_restaurent/admin
```

or

```
http://localhost/Apna_restaurent/admin/index.php
```

---

# 📁 Project Structure

```
Apna_restaurent/
│
├── admin/
├── css/
├── js/
├── images/
├── database/
│     └── maher.sql
├── index.php
├── login.php
├── register.php
├── menu.php
├── gallery.php
├── contact.php
└── README.md
```

---

# 🛠 Common Errors

## MySQL not running

Open XAMPP and start **MySQL**.

---

## Apache not running

Close applications using Port 80 or change the Apache port.

---

## Database Connection Error

Verify:

- MySQL is running.
- Database name is **maher**.
- SQL file has been imported successfully.

---

## Page Not Found

Ensure the project is located inside:

```
C:\xampp\htdocs\Apna_restaurent
```

---

# 📖 Project Workflow

```
Start XAMPP
       │
       ▼
Start Apache & MySQL
       │
       ▼
Create Database
       │
       ▼
Import maher.sql
       │
       ▼
Copy Project to htdocs
       │
       ▼
Open localhost/Apna_restaurent
```

---

# 👨‍💻 Developed By

**Project:** Apna Restaurant Management System

Technology Stack:

- PHP
- MySQL / MariaDB
- HTML
- CSS
- JavaScript
- Bootstrap

---

# 📄 License

This project is intended for educational and academic purposes only.
