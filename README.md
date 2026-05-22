# Student Management API

A RESTful backend application built using FastAPI for managing student records with CRUD operations, request validation, and database integration.

This project demonstrates practical backend development concepts including API routing, database operations, structured validation, and modular backend architecture.

---

## Overview

The API allows users to create, retrieve, update, and delete student records through structured REST endpoints. The application is designed using FastAPI and SQLAlchemy with a clean modular architecture for maintainability and scalability.

---

## Tech Stack

### Backend
- Python
- FastAPI
- SQLAlchemy
- MySQL

### Tools
- Postman
- Git & GitHub

---

## Features

- Create student records
- Retrieve all students
- Fetch student details by ID
- Update existing student data
- Delete student records
- Request validation using Pydantic
- Structured exception handling
- Modular API routing
- Database integration with MySQL

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/students` | Create student |
| GET | `/students` | Retrieve all students |
| GET | `/students/{id}` | Retrieve student by ID |
| PUT | `/students/{id}` | Update student |
| DELETE | `/students/{id}` | Delete student |

---

## Project Structure

```bash
student-management-api/
│
├── app/
│   ├── routes/
│   ├── models/
│   ├── schemas/
│   ├── database/
│   └── main.py
│
├── requirements.txt
├── README.md
└── .env.example
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/kushagranayak55-web/student-management-api.git
```

### Setup

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## Learning Outcomes

This project helped in understanding:

- REST API development with FastAPI
- CRUD operation workflows
- Database integration using SQLAlchemy
- Request validation using Pydantic
- API testing using Postman
- Backend project structuring

---

## Status

Completed and open for future feature enhancements.

---

## Author

Kushagra Nayak

LinkedIn:
https://www.linkedin.com/in/kushagra-nayak-99786a305

GitHub:
https://github.com/kushagranayak55-web
