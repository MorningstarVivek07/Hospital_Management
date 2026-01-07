Hospital Management System (Django)

Overview

The Hospital Management System is a web-based application developed using Django that streamlines hospital operations by managing patients, doctors, appointments, billing, and administrative workflows in a centralized system. The application is designed to improve efficiency, data accuracy, and accessibility for hospital staff.

Key Features

User Authentication & Authorization (Admin / Staff)

Patient Management (Add, Update, View records)

Doctor Management

Appointment Scheduling

Billing & Reports

Secure Data Handling

Responsive Web Interface

Technology Stack

Backend: Python, Django

Frontend: HTML, CSS, Bootstrap

Database: SQLite (can be configured to MySQL / PostgreSQL)

Version Control: Git & GitHub
Project Structure

Hospital-Management-System/
│
├── hospital_app/
├── templates/
├── static/
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md

Installation & Setup
Prerequisites

Python 3.9+

Git

Virtual Environment (recommended)

Step 1: Clone the Repository
git clone https://github.com/USERNAME/Hospital-Management-System.git
cd Hospital-Management-System

Step 2: Create Virtual Environment
python -m venv venv


Activate it:

Windows

venv\Scripts\activate


Linux / macOS

source venv/bin/activate

Step 3: Install Dependencies
pip install -r requirements.txt

Step 4: Apply Migrations
python manage.py makemigrations
python manage.py migrate

Step 5: Create Superuser
python manage.py createsuperuser

Step 6: Run the Server
python manage.py runserver


Open browser and visit:

http://127.0.0.1:8000/

Usage

Login as Admin to manage doctors, patients, and appointments

Staff users can view and manage assigned records

Data is securely stored and managed via Django ORM

Screenshots

(Add screenshots of Dashboard, Patient List, Appointment Page here)

Security Notes

Sensitive data (SECRET_KEY, DB credentials) are excluded using .gitignore

Environment variables should be used for production deployment

Future Enhancements

Role-based access control (RBAC)

Online payment integration

Email & SMS notifications

REST API for mobile application

Deployment on cloud (AWS / Render)

Author

Vivek Chauhan
Data Analyst & Django Developer
GitHub: https://github.com/MorningstarVivek07

License

This project is developed for educational and portfolio purposes.
You may modify and use it with proper attribution.
