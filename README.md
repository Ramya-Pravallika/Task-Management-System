# Task Management System (Python/Flask/SQL)

## Features
- User authentication (register, login, logout)
- Task CRUD (create, update, delete, list)
- Task assignment
- Dashboard with task list

## Tech Stack
- Python 3.x
- Flask (web framework)
- SQLAlchemy (ORM, SQLite by default)
- Jinja2 (templates)
- Linux (deployment & usage)

## Setup Instructions

### Install dependencies
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Initialize the database
```bash
flask db init
flask db migrate -m "Initial migration."
flask db upgrade
```

### Run the app
```bash
flask run
```

### Default Admin Login
User: admin  
Password: admin

## Directory Structure
- app/: Source code (models, routes, templates, static)
- migrations/: Database migrations
- requirements.txt: Python dependencies
- run.py: App runner
