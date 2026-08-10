# FastAPI Blog

A backend-focused blog application built with **FastAPI**, designed to explore modern API development, database integration, authentication, and server-side web development.

## 🛠️ Tech Stack

### Backend

* Python
* FastAPI
* Uvicorn

### Database

* PostgreSQL
* SQLAlchemy
* SQlite
* Alembic

### Validation & Authentication

* Pydantic
* Pydantic Settings
* Passlib
* python-jose

### Frontend

* HTML
* CSS
* Jinja2 Templates

### Development Tools

* Git
* GitHub
* VS Code

## 📋 Planned Features

* User registration and authentication
* Secure password hashing
* User profiles
* Create, read, update, and delete blog posts
* PostgreSQL database integration
* Database migrations with Alembic
* Request and response validation
* Protected API routes
* Server-side HTML templates
* Interactive API documentation with Swagger UI and ReDoc

## 📂 Project Structure

```text
FastAPI_Blog/
│
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

The project structure will be expanded as additional application components are implemented.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/FastAPI-Blog.git
cd FastAPI-Blog
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Start the FastAPI development server:

```bash
fastapi dev main.py
```

The application will be available at:

```text
http://127.0.0.1:8000
```

## 📖 API Documentation

FastAPI automatically generates interactive API documentation.

### Swagger UI

```text
http://127.0.0.1:8000/docs
```

### ReDoc

```text
http://127.0.0.1:8000/redoc
```

## 🎯 Project Overview

The project focuses on building a structured blog application while exploring the core concepts of modern Python backend development.

It covers API development with FastAPI, relational database management with PostgreSQL, ORM-based database interaction with SQLAlchemy, schema validation with Pydantic, authentication, and server-side rendering.

