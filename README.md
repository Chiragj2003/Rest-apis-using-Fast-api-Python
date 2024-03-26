# Blog Management API

This project implements a RESTful API for managing a simple blog system using FastAPI, a modern web framework for building APIs with Python. The API provides endpoints for creating, retrieving, and managing blog posts and comments.

## Features

- **Create Blog Post**: Allows users to create new blog posts with a title, body, and optional published status.
- **Retrieve Blog Post**: Retrieves a specific blog post by its ID.
- **List Published Blogs**: Retrieves a list of published blogs with options to limit and sort them.
- **List Unpublished Blogs**: Retrieves a list of all unpublished blogs.
- **Retrieve Comments**: Retrieves comments for a specific blog post by its ID.

## Requirements

- Python 3.7+
- FastAPI
- Pydantic
- Sqlalchemy
- 
## Installation

1. Clone the repository:

    ```
    git clone https://github.com/your_username/blog-management-api.git
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the FastAPI server:

    ```
    uvicorn main:app --reload
    ```

2. Access the API via http://localhost:8000 in your browser or any HTTP client.


## Documentation

- Swagger UI: Visit http://localhost:8000/docs to interactively explore the API endpoints using Swagger UI.
- ReDoc: Visit http://localhost:8000/redoc to view the API documentation in ReDoc.


