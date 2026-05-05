# Library_Management_System
# 📚 Library Management System (LMS)

A web-based Library Management System built using Django. This application helps manage users, book inventory, and transactions such as issuing and returning books.

---

## 🚀 Features

* 👤 User Authentication (Register / Login)
* 📖 Book Inventory Management
* 🔄 Issue and Return Books
* 📊 Transaction Tracking
* 🧾 Admin Panel Support
* 🌐 REST API Support (Serializers included)

---

## 🏗️ Project Structure

```
library_system/
│── manage.py
│── db.sqlite3
│
├── library_system/        # Main project settings
│   ├── settings.py
│   ├── urls.py
│
├── accounts/              # User management
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── templates/
│
├── inventory/             # Book inventory management
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── templates/
│
├── transactions/          # Book issue/return system
│   ├── models.py
│   ├── views.py
│
└── dataDB.py              # Database helper / custom logic
```

---

## ⚙️ Tech Stack

* Backend: Django (Python)
* Database: SQLite (default)
* Frontend: HTML Templates
* API: Django REST Framework

---

## 🔧 Installation & Setup

### 1️⃣ Clone the repository

```
git clone <your-repo-link>
cd LMS/library_system
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```
pip install django djangorestframework
```

### 4️⃣ Apply Migrations

```
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run the Server

```
python manage.py runserver
```

---

## 🌐 Usage

* Open browser: http://127.0.0.1:8000/
* Admin Panel: http://127.0.0.1:8000/admin

Use the system to:

* Register/Login users
* Manage books
* Issue and return books
* Track transactions

---

## 📌 Modules Overview

### 🔐 Accounts

* Handles user registration and login
* Templates include login and registration pages

### 📚 Inventory

* Manages books data
* Add, update, and delete books

### 🔄 Transactions

* Handles issuing and returning books
* Maintains borrowing history

---

## 📈 Future Improvements

* JWT Authentication
* Late fee calculation
* Book search & filters
* Improved UI (Bootstrap / React)
* Role-based access (Admin / Student)

---

## 🤝 Contribution

1. Fork the repository
2. Create a new branch
3. Make changes
4. Submit a pull request

---

## 📄 License

This project is open-source and intended for learning purposes.

---

## 💡 Author

Developed as a learning project to understand Django architecture, backend development, and REST APIs.
