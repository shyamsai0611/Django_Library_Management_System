# Django Library System

A web-based library management system built with Django. This project aims to provide a user-friendly interface for managing library resources, including books, authors, and borrowers.

## Features

- User authentication and authorization
- Manage books (add, update, delete)
- Manage authors (add, update, delete)
- Issue and return books
- Search functionality for books and authors
- Responsive design

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python (3.8 or higher)
- Django (3.2 or higher)
- Git


Installation
=============
1. Clone the repository:
   
git clone https://github.com/shyamsai0611/Django_Library_System.git

cd your-repo-name


2. Apply the make migrations and migrate:
   
python manage.py makemigrations

python manage.py migrate


3. Create a superuser:
   
python manage.py createsuperuser


5. Run the development server:
   
python manage.py runserver

Usage
======
1. Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view the site.
2. Log in with the superuser account you created.
3. Start managing your library resources.

Project Structure
=================
- **library/**: Main Django project directory
- **library_app/**: Django app containing the core functionality
- **templates/**: HTML templates
- **static/**: Static files (CSS, JavaScript, images)

