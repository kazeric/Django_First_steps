# Django_First_steps
This project is a simple Django REST API for managing users, demonstrating basic CRUD (Create, Read, Update, Delete) operations using Django and Django REST Framework.

## Features

- List all users
- Create a new user
- Retrieve, update, or delete a user by ID

## API Endpoints

| Method | Endpoint              | Description         |
|--------|-----------------------|---------------------|
| GET    | `/api/users/`         | List all users      |
| POST   | `/api/users/create/`  | Create a new user   |
| GET    | `/api/users/<id>/`    | Retrieve a user     |
| PUT    | `/api/users/<id>/`    | Update a user       |
| DELETE | `/api/users/<id>/`    | Delete a user       |

## Requirements

- Python 3.8+
- Django 5.2.x
- djangorestframework
