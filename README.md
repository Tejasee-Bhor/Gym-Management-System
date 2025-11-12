# 🏋️ Gym Management System

The **Gym Management System** is a web application built using **Python, Django, and SQLite** that digitizes gym operations. It showcases practical skills in **web development, backend logic, database management, and application deployment**, simulating real-world workflows for both gym members and administrators.

## 🌟 Project Overview
This system replaces manual gym processes with a **centralized digital platform**. Users can **register, view membership plans, book classes, manage profiles, and track history**, while admins can **monitor bookings, manage categories and packages, track payments, and generate reports** from a single dashboard.

### Key Modules
- **Dashboard / Home:** Overview of gym facilities, schedules, events, and membership plans.  
- **User Management:** Handles user registration, login, membership booking, profile updates, and inquiries.  
- **Admin Management:** Full control for admins to manage categories, packages, bookings, payments, and reports.

## 🚀 Features
- Smooth user experience for members and admins.  
- Automated management of bookings, memberships, and payments.  
- Real-time admin dashboard for monitoring operations.  
- Modular architecture for maintainability and scalability.

## 💻 Getting Started

```bash
1.Activate virtual environment 
python -m venv venv
venv\Scripts\activate

2. Install Django
pip install django

3.Create superuser
python manage.py createsuperuser

4.Run migrations
python manage.py makemigrations
python manage.py migrate

5.Start server
python manage.py runserver

Note: This project was developed with reference to tutorials from Panjwani Softwares www.youtube.com/@PanjwaniSoftwares, which helped guide the project structure and implementation.
