# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API with Python and the FastAPI framework. You'll create endpoints for managing a collection of resources, validate request data, and return clear HTTP responses while practicing API design and server-side programming.

## 📝 Tasks

### 🛠️ Create the FastAPI Application

#### Description
Set up a FastAPI application that exposes a RESTful API for managing a collection of books. Store the books in memory while the application is running and use Pydantic models to define and validate request data.

#### Requirements
Completed program should:

- Create a FastAPI application that can be started with Uvicorn.
- Define a Pydantic model with required fields for a book, such as `id`, `title`, `author`, and `year`.
- Implement `GET /books` to return all books.
- Implement `GET /books/{book_id}` to return one book or a `404 Not Found` response when the ID does not exist.
- Implement `POST /books` to validate and add a new book, returning an appropriate success status.

### 🛠️ Add Update and Delete Operations

#### Description
Complete the CRUD API by adding endpoints that update or remove books. Test each endpoint using the automatically generated FastAPI documentation.

#### Requirements
Completed program should:

- Implement `PUT /books/{book_id}` to update an existing book and return `404 Not Found` when the ID does not exist.
- Implement `DELETE /books/{book_id}` to remove an existing book and return `404 Not Found` when the ID does not exist.
- Return JSON responses with clear, consistent data.
- Use appropriate HTTP status codes for successful requests and errors.
- Verify the API using the interactive documentation at `/docs` and include examples of successful and unsuccessful requests.
