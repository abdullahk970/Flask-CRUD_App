# 🧾 Flask CRUD App (Intermediate)

> A simple yet production-style CRUD web application built with **Flask** and **Flask-SQLAlchemy**, demonstrating clean backend architecture, form handling, and database operations.

![Flask](https://img.shields.io/badge/Flask-Python-black)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-red)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 🚀 Overview

This project is a **CRUD (Create, Read, Update, Delete) application** built using Flask. It is designed for learning and demonstrating how to build a structured backend application with database integration and UI-driven workflows.

The app focuses on **clean structure, validation, and usability**, making it suitable for intermediate-level Flask developers.

---

# ✨ Features

### 📋 Listing System

* Paginated item listing
* Search functionality
* Clean tabular UI

### ➕ Create & ✏️ Edit

* Form-based input
* Server-side validation
* Reusable form structure

### 🔍 Detail View

* Individual record view
* Clean and readable layout

### 🗑️ Delete Functionality

* Safe delete with confirmation
* Prevent accidental deletion

---

# 🏗️ Tech Stack

* Flask (Backend Framework)
* Flask-SQLAlchemy (ORM)
* SQLite / PostgreSQL (Database)
* HTML / Jinja2 Templates
* Bootstrap (Optional UI styling)

---

# 📂 Project Structure

```text id="flask-crud-structure"
flask-crud/
│
├── app/
│   ├── __init__.py
│   ├── models.py
│   ├── routes.py
│   ├── forms.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── list.html
│   │   ├── detail.html
│   │   ├── create.html
│   │   └── edit.html
│   └── static/
│
├── config.py
├── requirements.txt
├── run.py
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash id="clone-flask-crud"
git clone https://github.com/yourusername/flask-crud-app.git

cd flask-crud-app
```

---

## Create Virtual Environment

```bash id="venv-flask"
python -m venv venv
```

Activate:

**Windows**

```bash id="activate-win"
venv\Scripts\activate
```

**Linux / Mac**

```bash id="activate-linux"
source venv/bin/activate
```

---

## Install Dependencies

```bash id="install-flask"
pip install -r requirements.txt
```

---

## Run Application

```bash id="run-flask"
python run.py
```

App will run at:

```text id="port-flask"
http://127.0.0.1:5000
```

---

# 🧠 Core Functionality

### 📄 List Page

* Displays all records
* Search by keyword
* Pagination support

### ➕ Create Record

* Input form
* Validation handling
* Database insertion

### ✏️ Edit Record

* Pre-filled form
* Update existing data
* Validation before saving

### 🔍 Detail Page

* View full record information

### 🗑️ Delete Record

* Confirmation prompt
* Safe deletion from database

---

# 🔄 CRUD Flow

```text id="crud-flow"
User Action
   ↓
Flask Route
   ↓
Form Validation (if needed)
   ↓
SQLAlchemy ORM Operation
   ↓
Database Update
   ↓
UI Response (Template Render)
```

---

# 📌 Key Highlights

* Clean MVC-style structure
* SQLAlchemy ORM integration
* Server-side validation
* Pagination + Search
* Reusable Jinja templates
* Beginner-friendly but production structured

---

# 🚀 Future Improvements

* 🔐 Authentication & Login System
* 📊 Admin Dashboard
* 📦 REST API Version (Flask RESTful)
* 🌐 React Frontend Integration
* ☁️ Deployment (Render / Heroku / AWS)
* 🧪 Unit Testing (PyTest)
* 📈 Analytics Panel

---

# 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push branch
5. Open Pull Request

---


# 👨‍💻 Author

**Muhammad Abdullah Khan**



## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
