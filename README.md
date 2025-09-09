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


🧪 Testing the API with Postman

I used Postman to test all the API endpoints during development. Postman allowed me to quickly simulate and validate HTTP requests and ensure that the API behaved as expected for different scenarios (e.g., successful requests, missing parameters, invalid IDs).

Here are some Postman requests you can use:

GET all destinations:

Method: GET

URL: http://127.0.0.1:5000/destinations

GET a specific destination:

Method: GET

URL: http://127.0.0.1:5000/destinations/1

POST a new destination:

Method: POST

URL: http://127.0.0.1:5000/destinations

Body (JSON):

{
  "destination": "London",
  "country": "UK",
  "rating": 4.5
}


PUT to update a destination:

Method: PUT

URL: http://127.0.0.1:5000/destinations/1

Body (JSON):

{
  "destination": "London City",
  "country": "UK",
  "rating": 4.8
}


DELETE a destination:

Method: DELETE

URL: http://127.0.0.1:5000/destinations/1

🔧 Future Improvements

User Authentication: Implement user authentication and authorization for access control.

Pagination: Implement pagination for the /destinations endpoint to handle large datasets.

Data Validation: Add input validation and error handling for incoming data.
