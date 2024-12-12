# Atelier MVC - Laravel User Management System

## 📋 Project Description
A robust Laravel application demonstrating a complete Model-View-Controller (MVC) implementation for user management. This project serves as an educational tool and practical example of building web applications using the Laravel framework. (it helps you understand the basics of laravel)

---

## ✨ Features
- Create new users with validation.
- View a complete user list.
- Edit existing user information.
- Delete user records.
- Responsive and simple user interface.
- Comprehensive error handling.

---

## 🚀 Technologies Used
- **Framework:** Laravel 10.x
- **Language:** PHP 8.x
- **Database:** MySQL
- **Templating Engine:** Blade
- **ORM:** Eloquent

---

## 🛠️ Prerequisites
Ensure the following tools and environment are set up:
- PHP 8.1+
- Composer
- MySQL
- A Laravel 10.x compatible development environment

---

## 📦 Installation Steps

### 1. Clone the Repository
```
git clone https://github.com/ayaberrou/atelier-mvc.git
cd atelier-mvc
```

### 2. Install Dependencies
```
composer install
```

### 3. Configure the Environment
```
cp .env.example .env
php artisan key:generate
```

### 4. Database Setup
- Create a MySQL database named `atelier_mvc`.
- Update the `.env` file with your database credentials:
  ```
  DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=atelier_mvc
  DB_USERNAME=your_username
  DB_PASSWORD=your_password
  ```

### 5. Run Migrations
```
php artisan migrate
```

### 6. Start the Development Server
```
php artisan serve
```

or follow the following doc: https://drive.google.com/file/d/1VAcjwIMKNErAk_LvjP_fcFYjIRTZL6Xe/view
---

## 🌐 Accessing the Application
- **User List:** [http://localhost:8000/users](http://localhost:8000/users)
- **Create User:** [http://localhost:8000/users/create](http://localhost:8000/users/create)

---

## 📝 Project Structure
```
atelier-mvc/
│
├── app/
│   ├── Models/
│   └── Http/
│       └── Controllers/
├── database/
│   └── migrations/
├── resources/
│   └── views/
│       └── users/
└── routes/
```
