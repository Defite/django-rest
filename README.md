# Django REST API

## Installation

1) clone repository to some folder (`django-rest` by default)
2) `cd django-rest`
3) `python3 -m venv env`
4) `source env/bin/activate`
5) Install dependencies via `pip install -r requirements.txt`
6) `cd djapi`
7) `django-admin startapp app`
8) `python manage.py migrate` # Sync database
9) `python manage.py createsuperuser --email admin@example.com --username admin` # Create initial user
10) `python manage.py runserver` # Run server

## Admin

Django Admin is available here [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

## API

API root is here [http://127.0.0.1:8000/](http://127.0.0.1:8000/). You must be logged in to access routes.
