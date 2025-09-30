# VideoMeet - Real-time Video Conferencing Platform

VideoMeet is a Django-based video conferencing application that enables users to create and join virtual meeting rooms with real-time communication capabilities.

---

## 🌟 Features

### 🔐 Authentication & Security
- User registration and login system
- Secure session management
- Protected routes with login requirements
- Password authentication

### 🎥 Video Conferencing
- Create and join meeting rooms
- Room-based video call system
- Real-time communication interface
- User-friendly meeting joining process

### 👤 User Management
- User profile handling
- Personalized dashboard
- Session management
- Secure logout functionality

---

## 🛠️ Technology Stack

### Backend
- Django - Web framework
- Django Authentication - User management
- Python - Server-side logic

### Frontend
- HTML/CSS/JavaScript - Client interface
- WebRTC - Real-time communication (to be implemented)
- Responsive Design - Mobile-friendly interface

### Security
- CSRF Protection - Cross-site request forgery prevention
- Session Security - Secure cookie handling
- Authentication Decorators - Route protection

---

## 📋 Prerequisites
- Python 3.8+
- Django 4.2+
- Modern web browser with WebRTC support

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd videomeet-project
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

