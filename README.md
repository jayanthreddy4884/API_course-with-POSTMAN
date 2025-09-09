# API_course-with-POSTMAN



# **Travel API with Flask and SQLAlchemy**

## 🚀 **Project Overview**

This is a RESTful API built using **Flask** and **SQLAlchemy**. It allows users to manage travel destinations with basic **CRUD** (Create, Read, Update, Delete) functionality. The data is stored in a SQLite database. This project is part of my journey to learn backend API development with Python, Flask, and SQLAlchemy. The API manages travel destinations, including their name, country, and rating.

Additionally, **Postman** was used extensively to test and implement these APIs, ensuring each endpoint works as expected and provides the correct responses.

---

## 📜 **Technologies Used**

- **Flask**: Micro web framework for building the API.
- **SQLAlchemy**: ORM (Object-Relational Mapping) tool for interacting with the database.
- **SQLite**: Lightweight database to store the destinations.
- **Python**: Programming language used for API logic and backend development.
- **Postman**: Tool used for testing and verifying API endpoints during development.

---

## 🛠️ **Features**

- **CRUD Operations**: 
  - **Create** a new destination
  - **Read** all destinations or a specific destination by ID
  - **Update** an existing destination
  - **Delete** a destination by ID
- **Database Integration**: 
  - SQLite database used for storing destination data.
  - Database tables are created and managed using SQLAlchemy.
- **API Endpoints**:
  - `/` – Welcome message.
  - `/destinations` – Get all destinations, or add a new destination.
  - `/destinations/<int:destination_id>` – Get, update, or delete a specific destination by ID.

---
