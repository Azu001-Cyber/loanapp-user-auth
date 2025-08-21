# Loan Management  Application  - User authentication  System

This project is part of a full-stack **Loan Management Application**.  
I built the **user authentication system** (login, signup, logout) that ensures users can securely access their accounts.

## Features
- User Registration (Signup)
- Email Verification During Registration 
- User Login with Email & Password
- User Logout
- Form Validation
- Secure Password Hashing

##  Tech Stack
- **Backend:** Django
- **Frontend:** HTML, CSS (Bootstrap), Javascript 
- **Database:** SQLite (can be swapped for PostgreSQL/MySQL)
- **Other Tools:** Django Crispy Forms, Decouple for environment variables

  ## Installtion
  1. Clone the repository:
     ```bash
     git clone
  2. Navigate into the project folder
     ```cd loan_app_02

  3. Create and activate a virtual enviroment:
     ```bash
     python -m venv .venv #create venv
     source .venv/bin/activate #activate venv On Linux/Mac
     .venv/scripts/activate #activate venv on windows
  4. Install dependencies
     ```bash
     pip install -r requirememts.txt
  5. Make and Apply migrations
     ```bash
     python manage.py makemigration
     python manage.py migrate
  6. Run development server
     ```bash
     python manage.py runserver 
