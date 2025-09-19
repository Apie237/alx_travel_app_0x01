# ALX Travel App API

This project provides CRUD API endpoints for managing travel **Listings** and **Bookings** using Django REST Framework.

## Features
- CRUD operations for Listings and Bookings
- RESTful endpoints
- Swagger documentation for easy testing

## Endpoints
- `/api/listings/` → List & create listings
- `/api/bookings/` → List & create bookings
- `/swagger/` → Interactive API docs

## Setup
```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
