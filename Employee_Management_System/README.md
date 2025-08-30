# Office Employee Management System

A Django-based web application to manage office employees, their departments, roles, and related details.  
This project is built as part of a Python-Django tutorial for learning purposes.

---

## Features

- **Add Employees:** Create new employee records with name, department, and role.
- **View Employees:** See the full list of employees in the organization.
- **Filter Employees:** Search/filter employees based on department or role.
- **Update Employees:** Modify existing employee details.
- **Delete Employees:** Remove employee records when needed.
- **Simple UI:** Clean HTML templates for easy navigation and management.

---

## Tech Stack

- **Backend:** Python 3, Django
- **Database:** SQLite 
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Environment:** Virtualenv 

---

## Project Structure
EMPLOYEE_MANAGEMENT_SYSTEM/
├── db.sqlite3
├── manage.py
├── emp_app/ # Main Django application
│ ├── init.py
│ ├── admin.py # Admin panel configuration
│ ├── apps.py
│ ├── migrations/ # Database migration files
│ │ ├── init.py
│ │ └── 0001_initial.py
│ ├── models.py # Database models (Employee, Department, Role)
│ ├── tests.py
│ ├── urls.py # App-specific routes
│ ├── views.py # Application logic
│ ├── templates/ # HTML templates
│ │ ├── add_emp.html
│ │ ├── filter_emp.html
│ │ ├── index.html
│ │ ├── remove_emp.html
│ │ └── view_all_emp.html
│ └── pycache/ # Compiled Python files
└── office_emp_proj/ # Django project configuration
├── init.py
├── settings.py
├── urls.py
└── wsgi.py
