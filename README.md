# 📝 Task Manager

A simple and modern **Task Management Web Application** built using:

- **Django** (Backend)
- **PostgreSQL** (Database)
- **Tailwind CSS** (Frontend Styling)
- **HTML Templates + Django Template Engine**
- **CRUD Functionality (Create, Read, Update, Delete)**
- **User Authentication (Login, Register, Logout)**

---

## 🚀 Features

### ✔ User Features
- Register a new account
- Login / Logout
- View all your tasks
- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as **complete / incomplete**

### ✔ Technical Features
- Authentication with Django's built-in auth system  
- PostgreSQL as the database (can be changed in `settings.py`)
- Tailwind CSS for modern UI
- Clean project structure
- Responsive design

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Django |
| Database | PostgreSQL |
| Frontend | Tailwind CSS |
| Template Engine | Django Templates |
| Version Control | Git & GitHub |

---
## 📂 Project Structure
task_manager/
├── config/
├── tasks/
├── templates/
│ ├── base.html
│ └── tasks/
│ ├── login.html
│ ├── register.html
│ ├── task_list.html
│ ├── task_form.html
│ └── task_confirm_delete.html
├── venv/
└── manage.py