initialize a django app using 

'python3 manage.py startapp appname'


The migrate command looks at the INSTALLED_APPS setting and creates any necessary database tables according to the database settings in your mysite/settings.py file and the database migrations shipped with the app

'python3 manage.py migrate'