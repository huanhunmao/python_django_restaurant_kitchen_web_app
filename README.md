# python_django_restaurant_kitchen_web_app

# init
```commandline
pip install django

python -m django --version

django-admin startproject mysite .

python manage.py startapp restaurant_menu

python manage.py runserver
```

```commandline
models.py 
    Create your models here.
mysite/settings.py
    INSTALLED_APPS  add app_name restaurant_menu
    
python manage.py makemigrations

 python manage.py migrate 

```