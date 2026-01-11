# Task manager

# About this program

This app is simple task manager.

# Getting started

You should rename file .env.example to .env and added value of variable environments

```
DATABASE_URL = !Path to your database!
DEBUG = !'True' if you want to use debug mode!
SECRET_KEY = !Key for Django settings!
POST_SERVER_ITEM_ACCESS_TOKEN = !Token for your rollbar account!
```

After this:

```
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py creatsuperuser
```

For start application:

```
python3 manage.py runserver
```

The application is locally available at [http://127.0.0.1:8000]

# Usage example

You can watch it at work here: https://greywolf-task-manager.herokuapp.com/
