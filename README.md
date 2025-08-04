# 📊 Company API – Django REST Framework Project

A backend API built with **Django 3.2** and **Django REST Framework** for managing company-related data such as employees, departments, or any other business logic.

---

## 🚀 Features

- Django 3.2 based project
- RESTful API using Django REST Framework (DRF)
- SQLite3 database (easy to use for development)
- DRF permissions and JSON-only responses
- Modular structure (`api` app included)

---

## 📁 Project Structure

```
companyapi/
├── api/ # Your core application logic (views, models, etc.)
├── companyapi/ # Django project settings
├── db.sqlite3 # SQLite database file
├── manage.py # Django management utility

yaml
Copy
Edit
---

##
---

## 🚀 Features

- Add company with social links (LinkedIn, Facebook, etc.)
- Token-based authentication
- Group permissions
- Simple and clean Django 3.2 REST backend

---

## ⚙️ Installation Steps

1. **Clone the Repository**

```bash
git clone https://github.com/muhammadumer33/companyapi.git
cd companyapi


---
Create a Virtual Environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
If you don’t have a requirements.txt, run:

bash
Copy
Edit
pip install django djangorestframework
Apply Migrations

bash
Copy
Edit
python manage.py migrate
Run the Development Server

bash
Copy
Edit
python manage.py runserver
Create a Superuser (Optional)

bash
Copy
Edit
python manage.py createsuperuser

---
