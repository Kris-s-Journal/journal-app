# journal-app
Tech Stack:



SetUp:
1. Setting Up the Backend (Django)

    Step 1.1: Create a Virtual Environment
        -cd backend
        -python3 -m venv venv
        -source venv/bin/activate
    Step 1.2: Install Django and Other Dependencies
        -pip install django djangorestframework django-allauth psycopg2-binary
        -pip freeze > requirements.txt
    Step 1.3: Create Django Project and App
        -django-admin startproject myproject .
        -django-admin startapp app

2. Setting Up the Frontend (Next.js)

    Step 3.1: Create a Next.js App
        -npx create-next-app@latest . --typescript
    Step 3.2: Install Frontend Dependencies 
        -npm install axios @tanstack/react-query next-auth @reduxjs/toolkit react-redux tailwindcss postcss autoprefixer


In the root directory my-fullstack-app, create a .gitignore file:


<!-- ///////// -->
 Running the Projects
Backend (Django)
Activate the virtual environment:


source venv/bin/activate
Run the Django development server:

python3 manage.py runserver

Frontend (Next.js)

Run the Next.js development server:


npm run dev


    


