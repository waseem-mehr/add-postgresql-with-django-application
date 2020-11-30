# add-postgresql-with-django-application
1.first of all install the package => pip install psycopg2-binary
2.go to heroku website and then Personal folder and select the web app
3.go to Resources tab and search the Heroku Postgres and install the add-on
4.after that click on -> icon
5.database tab is open
6.go to database settings
7.go to database credentials 
8.use these credentials in django settings.py
such as 
DATABASES = {
    'default': {
        'ENGINE': '',
        'NAME': '',  #database name
        'USER':'',
        'PASSWORD':'',
        'HOST':'',
        'PORT':'',
    }
}
#thats it , happy coding :)
