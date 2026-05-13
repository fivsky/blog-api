# Blog API

REST API for a blog with posts and comments.

## Stack
- Python 3
- Django 3.2+
- Django REST Framework
- JWT (Simple JWT)
- SQLite

## Features
- CRUD posts with nested comments
- JWT authentication
- Object-level permissions (only author can edit/delete)
- Pagination (5 posts per page)
- Browsable API

## Installation
```bash
git clone https://github.com/fivsky/blog-api.git
cd blog-api
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

