# BlogSpot - Django Blog Website

A full-stack blog web application built with Django. Users can register, sign in, create blog posts with images, edit or delete their posts, and interact through comments.

## Features

- User authentication (signup, signin, profile)
- Create, read, update, and delete blog posts
- Image upload for blog posts
- Comment support on posts
- Contact form
- Responsive frontend using HTML, CSS, Bootstrap, and JavaScript

## Tech Stack

- Python
- Django
- SQLite
- HTML/CSS/JavaScript
- Bootstrap

## Project Structure

- myproject: Django project configuration
- myapp: Main app with models, views, urls, and migrations
- templates: HTML templates
- static: CSS, JS, fonts, and vendor assets
- media: Uploaded images

## Requirements

- Python 3.10+ (recommended)
- pip

Dependencies are listed in requirements.txt.

## Installation

1. Open terminal in the project folder.
2. Create a virtual environment:

```powershell
python -m venv .venv
```

3. Activate virtual environment (Windows PowerShell):

```powershell
.\.venv\Scripts\Activate.ps1
```

4. Install dependencies:

```powershell
pip install -r requirements.txt
```

5. Apply migrations:

```powershell
python manage.py migrate
```

6. Start development server:

```powershell
python manage.py runserver
```

7. Open in browser:

http://127.0.0.1:8000/

## Optional Admin Setup

Create admin user:

```powershell
python manage.py createsuperuser
```

Admin panel URL:

http://127.0.0.1:8000/admin/

## Current Branding Links

- LinkedIn: https://www.linkedin.com/in/sayan-koley/

## License

This project is for educational and personal use.
