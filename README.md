# Student Management API

## 🚀 Overview
This project is a simple RESTful API built using Spring Boot to manage student data. It provides basic CRUD (Create, Read, Update, Delete) functionality and demonstrates a layered backend architecture.

## 🛠 Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Postman (for API testing)

## 📌 Features
- Create a new student
- Retrieve all students
- Get student by ID
- Update student details
- Delete student

## 🔗 API Endpoints
- POST /students → Add student  
- GET /students → Get all students  
- GET /students/{id} → Get student by ID  
- PUT /students/{id} → Update student  
- DELETE /students/{id} → Delete student  

## 🏗 Project Structure
- Controller: Handles HTTP requests  
- Service: Contains business logic  
- Repository: Interacts with database using JPA  

## 📦 Sample Response
```json
{
  "id": 1,
  "name": "John Doe"
}
