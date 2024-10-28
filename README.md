CampusCart is a web-based marketplace application developed for students within campus communities. It provides a secure and easy-to-use platform where students can buy, sell, and trade products and services, aiming to make campus commerce more efficient and accessible.

![View 1](https://github.com/user-attachments/assets/f808c241-36f3-4928-8b56-67e9bc086d14)
Items Listed
![View 2](https://github.com/user-attachments/assets/bbc94334-39f6-4858-ab37-df98fb222a7e)
Vendor Dashboard
![Vendor](https://github.com/user-attachments/assets/5182a304-1e55-44f1-b73e-1265bb1913a2)
Admin Dashboard
![Admin](https://github.com/user-attachments/assets/d83f3b4f-72f3-4f01-98ac-ddce6971f5cd)

Technology Stack
Frontend: HTML, CSS, JavaScript
Backend: PHP (or Laravel if applicable)
Database: MySQL
Deployment: Local Server

Getting Started
Prerequisites
PHP (version 8.0 or higher recommended)
MySQL
A local server environment (e.g., XAMPP, WAMP, MAMP)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/jashwinsingh11/CampusCartIS314Project.git
cd CampusCartIS314Project
Install dependencies (if using Laravel):

bash
Copy code
composer install
Set up the database:

Create a new MySQL database named campuscart.
Import any provided SQL file (e.g., database.sql) to initialize tables.
Configuration
Copy .env.example to .env:

bash
Copy code
cp .env.example .env
Update .env with database details:

plaintext
Copy code
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=campuscart
DB_USERNAME=root
DB_PASSWORD=your_password
Generate an application key (if using Laravel):

bash
Copy code
php artisan key:generate
Running the Application
Run migrations (if applicable):

bash
Copy code
php artisan migrate
Start the development server:

bash
Copy code
php artisan serve
Access the application at http://localhost:8000.
