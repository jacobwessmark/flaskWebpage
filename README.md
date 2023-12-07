# MonsterSpace

Welcome to MonsterSpace, a dynamic web application developed by Jacob Wessmark & Timothy Lundberg. Built with Flask, a micro web framework written in Python, MonsterSpace offers a platform for social interaction and content sharing.

## Features
- **User Authentication:** Implementing a secure login and registration system.
- **Profile Management:** Users can create and edit profiles, adding personal details and avatars.
- **Post Creation:** Enables users to create and share posts.
- **Responsive Design:** Utilizes Flask-Bootstrap for a responsive and visually appealing interface.

## Getting Started
To get started with MonsterSpace, follow these steps:

1. **Install Dependencies:**  
pip install -r requirements.txt


2. **Initialize Database:**
flask db init
flask db migrate
flask db upgrade

3. **Run the Application:**  
python main.py

## Technology Stack  
- **Flask:** A lightweight WSGI web application framework.
- **Flask-SQLAlchemy:** ORM and database toolkit for Flask.
- **Flask-Migrate:** For handling database migrations.
- **Flask-Login:** For managing user sessions.
- **Flask-WTF:** Integrating Flask with WTForms.
- **Flask-Bootstrap:** For Bootstrap integration with Flask.
