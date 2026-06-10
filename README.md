# Todo API

A simple REST API built with Django and Django REST Framework.

## Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | /api/todos/ | List all todos |
| POST | /api/todos/ | Create a todo |
| GET | /api/todos/1/ | Get a single todo |
| PUT | /api/todos/1/ | Update a todo |
| DELETE | /api/todos/1/ | Delete a todo |

## Tech Stack

- Python 3.13
- Django
- Django REST Framework
- SQLite
- uv (package manager)

## Setup

```bash
uv sync
uv run python manage.py migrate
uv run python manage.py runserver
```