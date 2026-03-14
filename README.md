# 📚 Bookstore REST API

## Project Overview

This project is a simple RESTful API for managing books in a bookstore.
The API allows users to perform CRUD operations such as creating, retrieving, updating, and deleting books.

The goal of this project is to understand how backend systems work using Web APIs, databases, and API testing tools.

---

## 🚀 Technologies Used

* ASP.NET Core Web API
* SQL Server
* Entity Framework Core
* Postman (for API testing)
* Git & GitHub

---

## ⚙️ How to Run the Project Locally

1. Clone the repository

git clone https://github.com/hira254/bookstore-api.git

2. Open the project in Visual Studio

3. Update the database

Run the following commands in Package Manager Console:

Add-Migration InitialCreate
Update-Database

4. Run the project

Press **F5** or click **Run** in Visual Studio.

The API will start at:

https://localhost:5001/api/books

---

## 📡 API Endpoints

### 1️⃣ Get All Books

GET /api/books

Returns a list of all books in the database.

---

### 2️⃣ Get Book by ID

GET /api/books/{id}

Returns a specific book based on the given ID.

---

### 3️⃣ Create a New Book

POST /api/books

Sample Request Body:

{
"title": "Atomic Habits",
"author": "James Clear",
"price": 20,
"isbn": "1234567890",
"publishedDate": "2018-10-16"
}

---

### 4️⃣ Update a Book

PUT /api/books/{id}

Updates the details of an existing book.

---

### 5️⃣ Delete a Book

DELETE /api/books/{id}

Deletes a book from the database.

---

## 🧪 API Testing

All endpoints were tested using Postman.

Example operations tested:

* Create book
* Get all books
* Get book by ID
* Update book
* Delete book

Screenshots of Postman requests and responses are included in the repository.

---

## 📌 Author
Backend Internship Task
Created by: Hira Zahoor Ahmed
Backend Internship Task
Created by: **Hira Zahoor Ahmed**
