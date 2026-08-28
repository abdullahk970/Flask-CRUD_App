# 🧾 Flask CRUD Web Application

> A basic CRUD web application built with Flask and Flask-SQLAlchemy, demonstrating server-side routing, database operations, HTML forms, and server-rendered templates.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-red)
![SQLite](https://img.shields.io/badge/SQLite-Database-blue)

---

## 📌 Overview

This project demonstrates the fundamental architecture of a Flask web application that performs Create, Read, Update, and Delete operations.

The application uses:

- Flask
- Flask-SQLAlchemy
- SQLite
- Jinja2 templates

The project was created as a backend learning project focused on understanding web application fundamentals and database interaction.

---

## ✨ Features

- 📋 Record listing
- ➕ Create records
- ✏️ Update records
- 👁️ View records
- 🗑️ Delete records
- ✅ Form handling
- 🗄️ SQLite database integration
- 🧩 Jinja2 server-rendered templates

---

## 🔄 CRUD Workflow

```
User Request
     ↓
Flask Route
     ↓
Form / Input Handling
     ↓
SQLAlchemy Operation
     ↓
SQLite Database
     ↓
Template Response
```

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Python |
| Web Framework | Flask |
| ORM | Flask-SQLAlchemy |
| Database | SQLite |
| Templates | Jinja2 |

---

## 📂 Project Structure

```
Flask-CRUD_App/
│
├── app.py
│   └── Flask application and routes
│
├── templates/
│   └── Jinja2 HTML templates
│
├── instance/
│   └── Application database/runtime data
│
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

- Python 3.x
- Git

### 1. Clone the Repository

```
git clone https://github.com/abdullahk970/Flask-CRUD_App.git

cd Flask-CRUD_App
```

### 2. Create a Virtual Environment

```
python -m venv venv
```

### Windows

```
venv\Scripts\activate
```

### Linux / macOS

```
source venv/bin/activate
```

### 3. Install Dependencies

```
pip install flask flask-sqlalchemy
```

### 4. Run the Application

```
python app.py
```

---

## 📚 Learning Outcomes

This project demonstrates foundational knowledge of:

- Flask routing
- HTML form handling
- Server-rendered web applications
- Jinja2 templates
- SQLAlchemy ORM
- SQLite database operations
- CRUD application patterns

---

## ⚠️ Scope

This is a basic Flask learning/project implementation.

For production use, additional engineering work would be required around:

- Authentication
- Authorization
- Security hardening
- Automated testing
- Database migration management
- Production configuration
- Deployment

---

## 🔮 Possible Improvements

- User authentication
- Role-based access
- REST API endpoints
- Pagination
- Search and filtering
- Automated testing
- Production deployment

---

## 👨‍💻 Author

**Muhammad Abdullah Khan**

- GitHub: https://github.com/abdullahk970
- LinkedIn: https://www.linkedin.com/in/muhammad-abdullah-khan-9b0980316?utm_source=share_via&utm_content=profile&utm_medium=member_android

---

## 📄 License

This project is licensed under the MIT License.
