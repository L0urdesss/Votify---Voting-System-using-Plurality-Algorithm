# Votify - Voting System using Plurality Algorithm

A simple **web-based voting system** built with **HTML/CSS** for the frontend and **PHP** for the backend.  
The system uses the **Plurality Algorithm** to count votes.

---

![Sample Screenshot](Sample.jpg)

---

## Features
- User-friendly web interface for voting
- Vote counting using the Plurality Algorithm
- Admin panel for managing candidates and voters
- MySQL database integration
- Local deployment with XAMPP

---

## Installation & Setup

### 1. Install XAMPP
Download and install [XAMPP](https://www.apachefriends.org/index.html), which includes:
- Apache HTTP Server  
- MariaDB (MySQL)  
- PHP  

### 2. Start Apache & MySQL
Launch **XAMPP Control Panel** and start **Apache** and **MySQL** modules.

### 3. Import Database
1. Open **phpMyAdmin** from the XAMPP Control Panel.  
2. Create a new database (e.g., `votify_db`).  
3. Import the provided `.sql` file into this database.

### 4. Project Location
Place the project folder inside the `htdocs` directory of your XAMPP installation:  
- **Windows**: `C:\xampp\htdocs\your_project_folder`  
- **macOS**: `/Applications/XAMPP/htdocs/your_project_folder`

### 5. Configure Database Connection
Open the project’s PHP config file (e.g., `config.php`) and update:
```php
$host = "localhost";
$user = "root";
$pass = "";
$db   = "votify_db";
