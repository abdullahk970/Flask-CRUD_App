# 🧾 Flask CRUD App

> A CRUD (Create, Read, Update, Delete) web application built with Flask and Flask-SQLAlchemy, demonstrating backend structure, form handling, and database operations with server-rendered templates.

![Flask](https://img.shields.io/badge/Flask-Backend-black) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-red) ![Python](https://img.shields.io/badge/Python-3.x-blue)

## ⚠️ Before you push this

Your repo has `__pycache__/` committed. Add a `.gitignore`:

```bash
echo "__pycache__/
*.pyc
instance/" > .gitignore

git rm -r --cached __pycache__
git add .gitignore
git commit -m "Add .gitignore, remove cache from tracking"
git push
```

## 🚀 Overview

A structured CRUD application for managing records through a web interface — built to demonstrate clean backend architecture, form validation, and database integration using Flask.

## ✨ Features

- Record listing with a clean tabular UI
- Create and edit records via server-side forms with validation
- Individual record detail view
- Delete with confirmation

## 🏗️ Tech Stack

- Flask (backend framework)
- Flask-SQLAlchemy (ORM)
- SQLite (database)
- HTML / Jinja2 templates

## 📂 Project Structure

```
Flask-CRUD_App/
│
├── app.py            # Flask application — routes, models, and app entry point
├── templates/         # Jinja2 HTML templates
├── instance/           # SQLite database (instance folder, Flask convention)
└── README.md
```

## ⚙️ Installation

```bash
git clone https://github.com/abdullahk970/Flask-CRUD_App.git
cd Flask-CRUD_App

python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate

pip install flask flask-sqlalchemy
```

## 🚀 Run

```bash
python app.py
```

App runs at `http://127.0.0.1:5000`.

## 🔄 CRUD Flow

```
User Action → Flask Route → Form Validation → SQLAlchemy ORM Operation → Database Update → Template Render
```

## 🔮 Possible Future Improvements

- User authentication
- REST API version (Flask-RESTful)
- Pagination and search on the listing page
- Unit tests (Pytest)

## 👨‍💻 Author

**Muhammad Abdullah Khan**
