# Django Bootstrap Starter Kit

#### Includes Bootstrap 5 and AbstractUser

## Installation

Use this repository as Django project template:

```
django-admin startproject --template https://github.com/igorims/django-project-template/archive/master.zip <projectname>
```

After that make migrations:

```
python manage.py makemigrations
```

```
python manage.py migrate
```

Run server:

```
python manage.py runserver
```

Note:
Whenever you need to call User, put this at the top of the file (e.g. in views.py, models.py):
```
from django.contrib.auth import get_user_model
User = get_user_model()
```
