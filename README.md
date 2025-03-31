# Django Basics Project

A basic Django project created for learning the fundamentals of the Django web framework. This project demonstrates basic concepts such as:

- Creating Django apps
- Defining models
- Creating views and templates
- URL routing
- Using the Django template engine

## Project Structure

The project structure is as follows:

```
Django_Basics/
├── manage.py           # Django's command-line utility for administrative tasks.
├── storefront/         # Main project directory
│   ├── __init__.py
│   ├── asgi.py           # ASGI configuration
│   ├── settings.py       # Project settings
│   ├── urls.py           # URL configuration
│   ├── wsgi.py           # WSGI configuration
├── playground/        # A Django app for playing around and learning
│   ├── __init__.py
│   ├── admin.py          # Admin configuration
│   ├── apps.py           # App configuration
│   ├── migrations/       # Database migrations
│   │   └── __init__.py
│   ├── models.py         # Data models
│   ├── urls.py           # App URL configuration
│   ├── views.py          # Views (logic for handling requests)
│   └── templates/      # HTML templates
│       └── hello.html
├── Pipfile             # Pipenv environment file
├── .gitignore          # Specifies intentionally untracked files that Git should ignore
└── README.md           # This file
```

## Technologies Used

- Python
- Django
- HTML

## Setup Instructions

1.  **Install Pipenv:**

    If you don't have Pipenv installed, you can install it using pip:

    ```bash
    pip install pipenv
    ```

2.  **Install Dependencies:**

    Navigate to the project directory in your terminal and install the project dependencies using Pipenv:

    ```bash
    pipenv install
    ```

3.  **Activate the Virtual Environment:**

    Activate the virtual environment:

    ```bash
    pipenv shell
    ```

4.  **Apply Migrations:**

    Apply the database migrations:

    ```bash
    python manage.py migrate
    ```

## How to Run

To start the project, use the following command:

```bash
python manage.py runserver
```

This will start the Django development server. You can then access the project in your web browser at `http://127.0.0.1:8000/playground/hello`.
