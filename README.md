# Django Note Taker

A simple Note Taker web application developed using Python and Django.

## Project Description

The Django Note Taker is a web-based application that allows users to manage their notes easily.

The project was developed using Django. I created a Django project and a Django application and implemented CRUD operations for managing notes.

Users can create new notes, view notes, edit existing notes, update notes, and delete notes.

## Features

* Create a new note
* View notes
* Edit notes
* Update notes
* Delete notes
* Simple and user-friendly interface
* URL routing using Django
* Database storage using SQLite

## Technologies Used

* Python
* Django
* HTML
* CSS
* SQLite
* Git
* GitHub

## Django Concepts Used

* Django Project
* Django App
* Models
* Views
* URLs
* Templates
* Forms
* CRUD Operations
* SQLite Database

## CRUD Operations

### Create

Users can create and save a new note.

### Read

Users can view the available notes.

### Update

Users can edit and update an existing note.

### Delete

Users can delete an existing note.

## Project Workflow

1. Created a Django project.
2. Created a Django application inside the project.
3. Created the required models for storing notes.
4. Created views to handle application functionality.
5. Configured URLs for different operations.
6. Created HTML templates for the user interface.
7. Connected the application with the SQLite database.
8. Implemented Create, Read, Update, and Delete operations.
9. Tested the application using the Django development server.

## How to Run

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Go to the project folder:

```bash
cd Notetaker
```

Install Django:

```bash
pip install django
```

Run migrations:

```bash
python manage.py migrate
```

Start the Django development server:

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

## Project Structure

```text
Notetaker/
│
├── manage.py
├── db.sqlite3
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── app/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── ...
│
└── templates/
    └── ...
```

## Future Improvements

* User authentication and login
* Search notes
* Categories for notes
* Improved UI
* Deployment to a cloud platform

## Author

**Indra Bareddy**

Python | Django | SQL | Git | Web Development
