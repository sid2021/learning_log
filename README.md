# Learning Log

This is a Journal application that lets users keep track of information they have learned about particular topics. Built with Django.

App is based on a project from the book [Python Crash Course](https://nostarch.com/pythoncrashcourse2e) by Eric Matthes.

## Built With

- [Django](https://www.djangoproject.com/)
- [SQLite](https://www.sqlite.org/index.html)

## Installation

```
$ git clone https://github.com/sid2021/learning_log.git
$ cd learning_log
```

If you want to use virtualenv (on Windows):

```
$ python -m venv venv
$ venv\scripts\activate
```

If you want to use virtualenv (on MacOS/Linux):

```
$ python3 -m venv venv
$ source venv/bin/activate
```

Install dependencies, create database and run app:

```
$ pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py createsuperuser
$ python manage.py makemigrations learning_logs
$ python manage.py migrate
$ python manage.py runserver
```

Go to `http://localhost:8000`.
