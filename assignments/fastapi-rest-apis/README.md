# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Learn how to build a RESTful API using the FastAPI framework, including request handling, response models, and automatic documentation.

## 📝 Tasks

### 🛠️ API Setup

#### Description
Create a FastAPI application and define the main API structure.

#### Requirements
Completed program should:

- Install and import FastAPI and Pydantic.
- Create a `FastAPI()` app instance.
- Define a data model using `BaseModel` for request and response bodies.

### 🛠️ CRUD Endpoints

#### Description
Implement endpoints for creating, reading, updating, and deleting resources.

#### Requirements
Completed program should:

- Define at least one `GET` endpoint to retrieve data.
- Define one `POST` endpoint to add a new item.
- Use `PUT` or `PATCH` to update an existing item.
- Use `DELETE` to remove an item.

### 🛠️ API Documentation and Testing

#### Description
Use the built-in FastAPI docs and simple tests to verify the API behavior.

#### Requirements
Completed program should:

- Use request and response models to validate data.
- Return appropriate HTTP responses for success and failure.
- Confirm the API works by testing it in the browser or with `curl`.
- Optionally open `/docs` or `/redoc` to view automatic API documentation.
