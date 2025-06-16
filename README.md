# BlogConnect 📝

**BlogConnect** is a PHP-based content management system that allows users to post, manage, and search blogs. It comes with a full admin panel for managing blog categories, posts, comments, and admin users. Built using PHP, MySQL, HTML, and Bootstrap.

---

## 📁 Project Structure

- `/admin-panel/` - Admin interface to manage posts, categories, comments, and users.
- `/SQL_FILE/BlogConnect.sql` - SQL file to import the database.
- `/Diagrams/Schema.png` - ER diagram of the database schema.
- `index.php` - Home page showing blog posts.
- `contact.php`, `search.php`, etc. - Core site functionalities.

---

## 🚀 Features

- Admin authentication (login/logout)
- Add/update/delete blog categories and posts
- Manage user comments and contact queries
- Blog search functionality
- Responsive layout with Bootstrap

---

## 🔧 Installation & Setup

### 📌 Requirements

- PHP >= 7.4
- MySQL or MariaDB
- Apache server (XAMPP, WAMP, LAMP, or MAMP)

---

### 🖥️ Running Locally

#### Step 1: Clone the Repo or Download ZIP

git clone https://github.com/amareshwar3/BlogConnect.git

OR extract the ZIP folder you downloaded.


#### Step 2: Move Project to Server Directory  

If using **XAMPP**:  

Move the **BlogConnect** folder into: 

C:\xampp\htdocs\

#### Step 3: Start XAMPP/WAMP

Open XAMPP Control Panel

Start Apache and MySQL


#### Step 4: Import the Database

Visit:

http://localhost/phpmyadmin

Click Import

Select the file:

SQL_FILE/BlogConnect.sql

Click Go

This will create a database with all necessary tables.


#### Step 5: Run the App

Visit your browser:

http://localhost/BlogConnect/

Admin Panel:

http://localhost/BlogConnect/admin-panel/

---

## 📚 Technologies Used
PHP
MySQL
Bootstrap 4
HTML5 & CSS3


