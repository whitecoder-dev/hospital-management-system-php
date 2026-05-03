# Hospital Management System - PHP & MySQL

A simple Hospital Management System developed using PHP and MySQL. This project is designed to manage basic patient records through a simple web-based interface.

The system allows users to add new patient details and view all saved patient records from the database.

---

## Repository Description

A simple PHP and MySQL based Hospital Management System for adding and viewing patient records.

---

## Project Overview

This project is a beginner-friendly Hospital Management System created for academic and learning purposes. It uses PHP for backend processing and MySQL for storing patient information.

The project includes a basic dashboard, patient registration form, patient list page, and database connection file.

---

## Features

- Add new patient records
- View all patient records
- Store patient details in a MySQL database
- Simple PHP and MySQL database connection
- Easy-to-understand code structure
- Suitable for academic projects and practice work

---

## Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- XAMPP / Localhost

---

## Project Structure

```text
hospital-management-system-php/
│
├── index.php
├── add_patient.php
├── view_patients.php
├── db.php
└── css/
    └── style.css
```

---

## Database Setup

Create a database named:

```sql
CREATE DATABASE hospital_db;
```

Then select the database:

```sql
USE hospital_db;
```

Create the patients table:

```sql
CREATE TABLE patients (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    age INT NOT NULL,
    medical_condition VARCHAR(255) NOT NULL
);
```

---

## Database Connection

Update the database connection details in `db.php` according to your local server settings.

Example:

```php
<?php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "hospital_db";

$conn = new mysqli($servername, $username, $password, $dbname);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>
```

If your MySQL server uses a custom port, update the server name like this:

```php
$servername = "localhost:3307";
```

---

## How to Run the Project

1. Download or clone this repository.
2. Extract the project folder if it is inside a ZIP file.
3. Copy the project folder into the XAMPP `htdocs` directory.

Example:

```text
C:\xampp\htdocs\hospital-management-system-php
```

4. Start Apache and MySQL from the XAMPP Control Panel.
5. Open phpMyAdmin in your browser.

```text
http://localhost/phpmyadmin
```

6. Create the database named `hospital_db`.
7. Create the required `patients` table using the SQL query given above.
8. Open the project in your browser.

```text
http://localhost/hospital-management-system-php/
```

---

## Source Code Access

The full project source code is provided as a password-protected ZIP file.

To get the ZIP password, please follow my GitHub profile and contact me through email or WhatsApp.

---

## Get ZIP Password

Follow my GitHub profile and send a message with your request.

Email:

```text
oshanda@whitecoder.online
```

WhatsApp:

```text
+94788778100
```

Message format:

```text
Hello, I followed your GitHub profile. Please send me the password for the Hospital Management System PHP project ZIP file.
```

---

## Educational Purpose

This project is created for learning and academic purposes. Students can use this project to understand how PHP and MySQL work together in a basic CRUD-style web application.

---

## Recommended GitHub Topics

```text
php
mysql
hospital-management-system
patient-management
web-application
crud-project
xampp
```

---

## Author

**Oshanda Geethanjana**  
Founder of **WhiteCoder**

Website:

```text
https://www.whitecoder.online/
```

Portfolio:

```text
https://oshandageethanjana.github.io/
```

---

## License

This project is shared for educational purposes only.

You are not allowed to resell, redistribute, or upload this project as your own work without permission.

---

## Support

If this project helped you, please consider following my GitHub profile and supporting my work.

Developed with care by **WhiteCoder**.
