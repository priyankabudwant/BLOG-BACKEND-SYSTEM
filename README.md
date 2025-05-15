# BLOG-BACKEND-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: B K PRIYANKA

INTERN ID: CT04DK48

DOMAIN: BACKEND DEVELOPMENT

DURATION: 4 WEEKS

MENTOR : NEELA SANTOSH

This is a Django-based backend system for a blogging platform. It provides APIs for user registration, authentication, creating blog posts, updating/deleting posts, and retrieving blog content. The system uses SQLite as the default database.

OUTPUT:

![Image](https://github.com/user-attachments/assets/f0fbc5a4-6ed5-46b9-ab58-756c9ca2d2fc)

![Image](https://github.com/user-attachments/assets/8666b45d-750b-4f92-a005-949cce9eb778)

![Image](https://github.com/user-attachments/assets/24c9d314-9909-4dc9-99ca-7af1fe1ee8e4)

## Features

- User Registration and Login (Token-based Authentication)
- Create, Update, Delete, and View Blog Posts
- Categorized Blogs and Tagging
- Admin Panel for managing content and users
- SQLite database (easy for development and testing)

## Tech Stack

- **Backend Framework**: Django (Python)
- **Database**: SQLite
- **Authentication**: Token-based (via Django REST Framework)

## Getting Started

### Prerequisites

- Python 3.x
- pip (Python package manager)
- Virtualenv (recommended)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/priyankabudwant/BLOG-BACKEND-SYSTEM.git
   cd BLOG-BACKEND-SYSTEM/blog_project
   ```
   ## 2. Create a virtual environment:
    
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate
    ```
    ## 3.Run migrations:
    ```bash
    python manage.py migrate
    ```
    ## 4.Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```
   ## 5. Start the development server:
    ```bash
    python manage.py runserver
    ```
   

