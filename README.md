# API_Tutorials

# 🚀 Python API Tutorial (FastAPI & Flask)

This repository contains two simple API projects demonstrating how to build RESTful APIs in Python using:

- FastAPI (modern, high-performance framework)
- Flask + SQLAlchemy (classic REST API with database)

The goal of this project is to provide a beginner-friendly introduction to building APIs and implementing CRUD operations.

---

## 📁 Project Structure
├── fastAPI.py # FastAPI CRUD example (in-memory storage)
├── restAPI.py # Flask API with SQLite database
├── README.md

---

## ⚡ Features

### FastAPI API
- CRUD operations (Create, Read, Update, Delete)
- Input validation using Pydantic
- Path parameter validation
- Error handling with HTTPException
- Search endpoint

👉 Example endpoint:
GET /users/{user_id}


---

### Flask API
- CRUD operations with a real database
- SQLite + SQLAlchemy ORM
- JSON responses
- Persistent data storage

👉 Example endpoint:
GET /destinations


---

## 🛠️ Installation

### 1. Clone the repo
git clone https://github.com/Toukennn/API_tutorials.git
cd API_tutorials


### 2. Create virtual environment
python -m venv api_env


### 3. Activate it
Windows (PowerShell):
.\api_env\Scripts\Activate.ps1


---

### 4. Install dependencies
pip install fastapi uvicorn flask flask_sqlalchemy


---

## 🚀 Running the APIs

### ▶️ Run FastAPI
uvicorn fastAPI:app --reload


Open:
- http://127.0.0.1:8000
- Docs: http://127.0.0.1:8000/docs

---

### ▶️ Run Flask API
python restAPI.py

Runs on:
http://127.0.0.1:5000


---

## 📌 Example Endpoints

### FastAPI

- `GET /users/{id}`
- `POST /users/{id}`
- `PUT /users/{id}`
- `DELETE /users/{id}`
- `GET /users/search/?name=Josh`

---

### Flask API

- `GET /destinations`
- `GET /destinations/{id}`
- `POST /destinations`
- `PUT /destinations/{id}`
- `DELETE /destinations/{id}`

---

## 🧠 What You Learn

- How REST APIs work
- Difference between FastAPI and Flask
- CRUD operations
- Data validation
- Working with databases (SQLite)
- Structuring backend logic

---

## 🔥 Future Improvements

- Add authentication (JWT)
- Connect FastAPI to a real database
- Add request validation for Flask API
- Dockerize the project
- Deploy to cloud (Render / Railway)

---

## 📄 License
This project is for educational purposes.
