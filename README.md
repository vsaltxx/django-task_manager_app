# Task Manager Application

This is a simple web application for managing tasks, written using Django.

## Description

Task Manager allows users to create, view, modify, and delete tasks. Each task can have a title and description.

## Features

- Add new tasks
- View a list of all tasks
- Delete a task

## Installation

1. Clone the repository:

git clone https://github.com/vsaltxx/django-task_manager_app.git

2. Install dependencies:

pip install -r requirements.txt

## Usage

1. Navigate to the project directory:

cd task-manager

2. Run the server:

python manage.py runserver

3. Open a web browser and go to `http://127.0.0.1:8000/`.

## Project Structure

- `task_manager/`: Main project directory
  - `settings.py`: Django project settings
  - `urls.py`: Main application routes
- `tasks/`: Task Manager application
  - `models.py`: Data models
  - `views.py`: Views
  - `templates/`: HTML templates
  - `migrations/`: Database migrations
  - `admin.py`: Admin interface settings

## Requirements

- Python 3.x
- Django 3.x


