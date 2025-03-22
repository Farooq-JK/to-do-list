# Task Manager

A simple and elegant task management application built with Django.

## Features

- Create, edit, and delete tasks
- Mark tasks as complete/incomplete
- Clean and modern user interface
- Responsive design for all devices

## Quick Start

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- Unix/MacOS:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Start the development server:
```bash
python manage.py runserver
```

6. Open your browser and visit `http://127.0.0.1:8000/`

## Usage

- Click "Add New Task" to create a task
- Check the checkbox to mark a task as complete
- Use the edit icon to modify a task
- Use the delete icon to remove a task

## Technologies Used

- Django 5.0.2
- Bootstrap 5
- Crispy Forms
- Python 3.x 