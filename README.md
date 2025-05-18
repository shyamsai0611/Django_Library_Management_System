# Django Library System

A web-based library management system built with Django. This project aims to provide a user-friendly interface for managing library resources, including books, authors, and borrowers.

---

## Features

- User authentication and authorization  
- Manage books (add, update, delete)  
- Manage authors (add, update, delete)  
- Issue and return books  
- Search functionality for books and authors  
- Responsive design  

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python (3.8 or higher)  
- Django (3.2 or higher)  
- Git  

### Installation

Clone the repository:

```bash
git clone https://github.com/shyamsai0611/Django_Library_System.git
cd Django_Library_System
```
### Apply migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```
### Create a superuser:
```bash
python manage.py createsuperuser
```
### Run the development server:
```
python manage.py runserver
```
### Usage
Open your web browser and go to http://127.0.0.1:8000/ to view the site.

Log in with the superuser account you created.

Start managing your library resources.

### Project Structure
Django_Library_System/
├── library/ # Main Django project directory
├── library_app/ # Django app containing the core functionality
├── templates/ # HTML templates
├── static/ # Static files (CSS, JavaScript, images)
├── manage.py # Django management script
└── README.md # Project documentation
