# add-postgresql-with-django-application
1.first of all install the package => pip install psycopg2-binary <br/>
2.go to heroku website and then Personal folder and select the web app<br/>
3.go to Resources tab and search the Heroku Postgres and install the add-on<br/>
4.after that click on -> icon<br/>
5.database tab is open<br/>
6.go to database settings<br/>
7.go to database credentials <br/>
8.use these credentials in django settings.py<br/>
such as <br/>
DATABASES = {<br/>
    'default': {<br/>
        'ENGINE': '',<br/>
        'NAME': '',  #database name<br/>
        'USER':'',<br/>
        'PASSWORD':'',<br/>
        'HOST':'',<br/>
        'PORT':'',<br/>
    }<br/>
}<br/>
#thats it , happy coding :)<br/>
