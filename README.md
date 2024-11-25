A Django Web App

This Django web app provides a platform for users to create, view, edit, and delete tweets. It also includes functionalities for user registration, authentication, and search.

Features:
  Tweet Management: Create, view, edit, and delete tweets.
  User Registration and Login: Secure user authentication for accessing tweet functionalities.
  Search: Find tweets based on keyword matches (case-insensitive) in the tweet text.

Installation:
  1. Clone the Clone the repository
  2. Create a virtual environment (recommended):
      python3 -m venv venv
      source venv/bin/activate  # Linux/macOS
      venv\Scripts\activate.bat  # Windows
  3. Install dependencies:
       pip install -r requirements.txt
  4. Set up your database:
       Follow Django's instructions for your chosen database backend (usually PostgreSQL, MySQL, or SQLite).
  5. Run migrations:
       python manage.py migrate
  6. Start the development server:
       python manage.py runserver

Usage:
  Visit http://127.0.0.1:8000/ in your browser.
  Register an account using the registration form.
  Log in after registration.
  Create, view, edit, and delete tweets as needed.
  Use the search bar to find tweets based on keywords.
