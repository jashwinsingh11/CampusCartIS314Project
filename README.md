![View 2](https://github.com/user-attachments/assets/089ace48-8ef2-451b-85c4-11b555521ef1)CampusCart
CampusCart is a web-based marketplace application developed for students within campus communities. It provides a secure and easy-to-use platform where students can buy, sell, and trade products and services, aiming to make campus commerce more efficient and accessible.

![View 1](https://github.com/user-attachments/assets/adfcadca-6afa-410a-aa58-58aa04ec4069)

![View 2](https://github.com/user-attachments/assets/246429b3-d20f-4d64-9cba-a10d53edebac)

![View 2](https://github.com/user-attachments/assets/1024be35-289a-42d8-a403-1935fe028d68)

![Admin](https://github.com/user-attachments/assets/1ec86091-2a82-4413-8149-65b8b470fc22)

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
