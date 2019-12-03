# gci-django-hello-world
# steps
1. first create a virtual environment in python 3 by commands:
    python -m venv /path/to/new/virtual/environment
    then run command 'source <venv>/bin/activate' to activate it
    because lots of programmers do this because it will minimize
    running into errors. your one project will need django vertion
    x.x and other x.y by using venv this problem will never arise
    
2. run pip install django
3. run command 'django-admin startproject your_project_name'
4. to run the server goto the directory that has manage.py in your project
   and run the command 'python manage.py runserver'

5. run the command 'python manage.py createsuperuser' to get access to the
  django-admin
 
6. for displaying pages in your website you have to deal with the views.py
  in your project folder this file interacts with the urls.py metioned below
  and gets action according to the http requests the fuctions in this module
  gets a argument named request and this pre-defined fuctionality can be
  accessed with the render fuction in django.shortcuts
  
7. there is a thing called app in django. it can be created with the command
 'python manage.py startapp' to deal with certain tasks in your website.
 and this is managed with models.py in your app
   eg:- products management app, costumer managment app, accounts managment app
        and so on
        
   Note: these apps should be focused on one task. if the app is expanding, 
         move the extra fuctions to another app
         
8. for browser request handling urls.py is used.

9. django apps also can be used inj other django projects by importing it 
   as a package
