# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Create a REST API using the FastAPI framework that allows managing a collection of books. This assignment will help you understand how to build web APIs, handle HTTP requests, and work with data models in Python.

## 📝 Tasks

### 🛠️ Set Up FastAPI Application

#### Description
Install FastAPI and create a basic application structure with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and uvicorn using pip
- Create a FastAPI application instance
- Define a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server and verify it works by visiting http://localhost:8000 in a browser


### 🛠️ Implement CRUD Operations

#### Description
Add endpoints to create, read, update, and delete books in your API. Use a simple in-memory list to store the book data.

#### Requirements
Completed program should:

- Define a Book model with fields: id (integer), title (string), author (string), year (integer)
- Implement GET /books to retrieve all books
- Implement POST /books to add a new book
- Implement GET /books/{id} to get a specific book by ID
- Implement PUT /books/{id} to update a book
- Implement DELETE /books/{id} to remove a book
- Handle cases where book ID doesn't exist (return 404)