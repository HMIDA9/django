# Student Management System

A Django CRUD application for managing student records.

## Features

### Core Features
- Complete CRUD operations
- SQLite3 database
- MVT architecture
- Virtual environment

### Bonus Features
- Beautiful homepage
- Authentication system
- Bootstrap CSS framework
- Image upload for student profiles
- Search functionality
- Pagination
- Responsive design

## Setup Instructions

1. Create and activate virtual environment:
```bash
python -m venv venv
venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

4. Create superuser:
```bash
python manage.py createsuperuser
```

5. Run development server:
```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000 to access the application.
