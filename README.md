# Web Task Manager

## Description
Web Task Manager is a simple task management application based on Flask and SQLAlchemy. It allows users to create, update, and delete tasks efficiently.

## Features
- Task creation, editing, and deletion.
- Data persistence using SQLAlchemy.
- Simple and user-friendly interface.

## Requirements
Before running the project, ensure you have the following dependencies installed:

```
SQLAlchemy~=2.0.31
Flask~=3.0.3
```

## Installation
1. Clone the repository:
   ```bash
   git clone <REPOSITORY_URL>
   cd <REPOSITORY_NAME>
   ```
2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python app.py  # Or the main application file
   ```
5. Access the application in your browser at `http://127.0.0.1:5000/`

## Usage
- Access the web interface to manage tasks.
- Add new tasks, edit or delete existing tasks.

## Contribution
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-new`).
3. Make your changes and commit them (`git commit -m "Added new feature"`).
4. Submit a pull request.
