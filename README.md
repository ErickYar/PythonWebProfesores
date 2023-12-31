# Python listado de profesor
- este proyecto es para ingresar  Empleados con nuevas modificación para el registro 
- El proyecto se realizo netamente en PYTHON with DJANGO  


Ese es mi inicio en **PYTHYON** 

# Install

este proyecto  se necesita install '**_PYTHON_**'

## Comando para utilizar en "Django" se porne el comando 

- '_pip install django_'

## Para crear una "Proyecto" en PYTHON  
- Es con el comando "_django-admin startproject AppWebInicio_"

## Para crear una "Aplicación" en PYTHON  
- Es con el comanndo "_django-admin startapp app_"
  - Este comando se poner dentro de la carpeta "AppWebInicio"

## se a utilizado los comando de:
- pip install crispy-bootstrap5
- pip install django-crispy-forms
## se a utilizado los comando de:
- primero se ejecuta este comando "py manage.py migrate" para tener la tabla creadas y después "py manage.py makemigrations "
## DATABASE:
- En este proyecto se utilizó db.sqlite3 como base de datos
   
## modificaciones que se realizar en el archivo "settings.py":
- INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'app',
    'crispy_forms',
    'crispy_bootstrap5',
]

- CRISPY_ALLOWED_TEMPLATE_PACKS = "bootstrap5"

- CRISPY_TEMPLATE_PACK = "bootstrap5"


## Para ejecutar este programa es con el
- comando "python manage.py runserver "

