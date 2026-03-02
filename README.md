Project Description

This is a basic Django web application that performs CRUD operations (Create, Read, Update, Delete) using Django Models and Forms.

The project allows users to:

➕ Add Student

📋 View Student List

✏️ Update Student

❌ Delete Student

🔐 Manage students using Django Admin Panel

🛠 Technologies Used

Python
Django
SQLite (default database)
HTML
Django Templates

File structure

mymodel/
│
├── manage.py
├── mymodel/
│   ├── settings.py
│   ├── urls.py
│
└── students/
    ├── models.py
    ├── views.py
    ├── forms.py
    ├── urls.py
    ├── admin.py
    └── templates/
        └── students/
            ├── student_list.html
            ├── add_student.html
            └── update_student.html
