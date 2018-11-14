initialize a django app using 

'python3 manage.py startapp appname'


The migrate command looks at the INSTALLED_APPS setting and creates any necessary database tables according to the database settings in your mysite/settings.py file and the database migrations shipped with the app

'python3 manage.py migrate'


start new app:
'python manage.py startapp polls'

That’ll create a directory polls, which is laid out like this:
polls/
    __init__.py
    admin.py
    apps.py
    migrations/
        __init__.py
    models.py
    tests.py
    views.py


