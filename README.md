
![alt text](<swagger screenshot.png>)
# ALX Travel App

A Django-based REST API project for managing travel-related listings.  
This project is set up with MySQL as the database, Celery & RabbitMQ for asynchronous tasks, CORS handling, and Swagger API documentation.

---

## 📌 Features
- Django REST Framework for API development
- MySQL database configuration using environment variables
- CORS headers enabled for cross-origin requests
- Celery + RabbitMQ for background task processing
- Swagger UI for interactive API documentation
- Modular app structure (`listings` app for managing travel listings)

---

## 📂 Project Structure
alx_travel_app/
│
├── alx_travel_app/ # Main project folder
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ ├── asgi.py
│ └── init.py
│
├── listings/ # API app
│ ├── models.py
│ ├── views.py
│ ├── serializers.py
│ ├── admin.py
│ ├── apps.py
│ └── migrations/
│
├── .env # Environment variables (not pushed to GitHub)
├── requirement.txt # Python dependencies
├── manage.py
└── README.md