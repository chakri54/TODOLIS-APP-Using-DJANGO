
# TODOLISt-APP-Using-DJANGO

## Project Title: Django Based To-Do List Application

### Description
This project is a  To-Do List Application built with the Django Framework. 
It allows users to manage their tasks efficiently by providing features such as task creation, updating, and deletion.
With a clean and responsive UI, this application demonstrates the fundamentals of building a Django-based CRUD application.
---

## Features

### Add Tasks:
- Users can create new tasks with a title and optional description.
- Tasks are displayed in a list immediately after creation.

### Task List:
- A comprehensive list of tasks with a checkbox to indicate completion status (read-only).
- Includes the task title and optional description.

### Edit Tasks:
- Update the details of existing tasks, including marking them as completed or changing descriptions.

### Delete Tasks:
- Remove tasks from the list with a confirmation prompt for safety.

### Responsive Design:
- Uses Bootstrap for a mobile-friendly, user-friendly interface.

---

## Technology Stack
- **Framework**: Django (Python)
- **Database**: MySQL
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Django views, models, and forms

---

## Future Improvements
- Add user authentication for personalized task management.
- Implement task priorities (e.g., High, Medium, Low).
- Include due dates for tasks with reminders.
- Deploy the application on platforms like AWS.
- Add pagination for better performance with large task lists.
- Use React Js and api

---

## Folder Structure

- **tasks/**: The Django app containing models, views, forms, and templates.
- **templates/**: HTML templates for task list, creation, editing, and deletion.
- **todolist/**: Django project-level settings and configuration files.
- 

# SETUP INSTRUCTIONS

**Run Migrations/**
- python manage.py makemigrations
- python manage.py migrate

- **Start the Development Server/**
- python manage.py runserver

## Project Folder Structure

todolist/
│
├── templates/               # Global templates folder
│   ├── base.html            # Base template with common layout
│   └── tasks/               # Nested under app templates folder
│       ├── task_list.html   # Task list page
│       ├── task_form.html   # Task form for create/edit
│       ├── task_confirm_delete.html  # Task deletion confirmation
│
├── tasks/                   # App folder
│   ├── migrations/          # Database migrations
│   │   ├── __init__.py      # Initialization for migrations
│   ├── forms.py             # Form definitions
│   ├── models.py            # Database models
│   ├── views.py             # Views for handling CRUD logic
│   ├── urls.py              # URL routing for the app
│   ├── __init__.py          # App initialization
│
├── todolist/                # Project folder
│   ├── __init__.py          # Project initialization
│   ├── asgi.py              # ASGI configuration
│   ├── settings.py          # Django settings
│   ├── urls.py              # Project-level URL routing
│   ├── wsgi.py              # WSGI configuration
│
│           
├── manage.py                # Django management commands
│
│
│

