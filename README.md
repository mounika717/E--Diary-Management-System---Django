# E--Diary-Management-System---Django
A Django-based web application to manage daily personal records with user authentication, CRUD operations, and a simple UI for journaling.
📝 E-Diary Management System

This is a Django-based web application that allows users to maintain their daily personal records securely. It offers essential features like user registration, login, add/edit/delete diary entries, and view past entries—all in one place.


🚀 Features

- User Registration and Authentication
- Create, Read, Update, Delete (CRUD) diary entries
- View past records by date
- Simple and clean UI
- SQLite database integration


 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Django (Python)
- **Database:** SQLite
- **Other:** Bootstrap (for styling), Django Templates


🔧 Setup Instructions

1. Clone the repository:
   git clone https://github.com/your-username/e-diary-management-django.git
   cd e-diary-management-django

2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies:
pip install -r requirements.txt

4. Apply migrations:
python manage.py migrate

5. Run the development server:
python manage.py runserver
