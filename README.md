# InvManager
# InvManager 📦  

**Inventory Management System** - Built with Django while learning web development  

[![Django](https://img.shields.io/badge/Django-5.2.5-brightgreen)](https://www.djangoproject.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0.2-blueviolet)](https://getbootstrap.com/)
[![License](https://img.shields.io/badge/License-MIT-orange)](LICENSE)

## Overview
As part of my Django learning journey, I built this full-featured inventory management system featuring:
- **CRUD Operations** (Create, Read, Update, Delete)
- **Responsive Bootstrap UI** with mobile-friendly design
- **Product management** with SKU tracking
- **Modern form handling** with Django Crispy Forms
- **Data validation** for inventory integrity


## Features ✨
- 📋 Product catalog with ID/SKU tracking
- 🔄 Add/Edit/Delete inventory items
- 📊 Responsive product tables with sorting
- 🛡️ Form validation and error handling
- 📱 Mobile-optimized interface

## Screenshots 📸

![image alt](https://github.com/iamohammed1/InvManager/blob/3dc7f10dc6a36e14eee192a399811c07858db2c5/home.png)
![image alt](https://github.com/iamohammed1/InvManager/blob/3dc7f10dc6a36e14eee192a399811c07858db2c5/list.png)
![Product List](https://github.com/iamohammed1/InvManager/blob/3dc7f10dc6a36e14eee192a399811c07858db2c5/products.png) 

## Tech Stack
- **Backend**: Django 5.2.5
- **Frontend**: Bootstrap 5
- **Database**: SQLite (default)
- **Forms**: Django Crispy Forms

## Installation ⚙️
```bash
# Clone repository
git clone https://github.com/iamohammed1/InvManager.git
cd InvManager

# Create virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Linux/Mac

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run development server
python manage.py runserver
