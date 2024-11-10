# Django Blog #
## Table of Contents 
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](installation)
- [Usage](usage)



## Introduction

-This project provides a basic example using a simple HTML template (index.html) with CSS styling. You can customize the HTML and CSS to match your desired design.
- Explore other Django functionalities to extend the project with features like user authentication, comments, pagination, and more.
Additional Notes
- This is a basic blog project and can be further enhanced based on your specific needs.

## Features
- Create, edit, and delete blog posts.
- List posts with title, date, and short excerpt on the homepage.
- View full post content on dedicated post detail pages.
- Clean and responsive layout using basic CSS styling.

## Prerequisites
- Python 3.x (https://www.python.org/downloads/)
- pip (package manager for Python) - usually comes bundled with Python
- A code editor or IDE (e.g., Visual Studio Code, PyCharm)

## Installation
- Clone this repository:

-Bash
-git clone https://github.com/Deepakjoy789/Django-Blog/


 Create a virtual environment (recommended):

-Bash
-python -m venv venv
-source venv/bin/activate  # Windows: venv\Scripts\activate

 Install dependencies:

- Bash
- pip install -r requirements.txt


 Set up your database:

- Edit mysite/settings.py to configure your database connection details.

 Run migrations to create the database tables:
Bash
-python manage.py migrate


 Run the development server:

Bash
- python manage.py runserver


This will start the Django development server, typically accessible at http://localhost:8000/ by default.

## Usage
 Create a new admin user:

Bash
- python manage.py createsuperuser


 Login to the admin panel:

- Go to http://localhost:8000/admin/ in your web browser.
- Use the credentials you created in step 1 to log in.
- Create and manage blog posts:
- Use the admin panel to manage blog posts. You can create new posts, edit existing posts, and delete posts.
Customization

