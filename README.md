# DEPENDENCIES
 - Python3.6.x or above
 - Python Virtualenv
 - Python Django 3.1.5 or above

# Setup
 - Setup env

 Create django-env

 ```
    virtualenv django-env
 ```

 Activate virtual env
 ```
    source django-env/bin/activate
 ```

 Install django
 ```
    pip3 install django
 ```
 Go to django project
 If you never run migrate run this
 ```
    python manage.py migrate
 ```
 Run server
 ```
    python manage.py runserver