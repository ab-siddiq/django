# django
# What is Django?
- Django is a Web application framework written in Python Programming language. It is based on the `MVT (Model View Template) design pattern`.
- It is also called a `battery included framework` because Django provides built-in features for everything.
# Why the Django framework?
- Excellent documentation and high scalability
- Used by top MNCs and Companies, such as Instagram, Spotify, YouTube, Bitbucket, Dropbox, etc. and the list is never-ending.
- Easiest Framework to learn, rapid development, and Batteries fully included.
- One can integrate Web scraping, Machine Learning, Image Processing, Scientific Computing, etc with web applications and do lots and lots of advanced stuff.
# Unique feature of Django
- Admin Interface
- Object-Relational Mapping (ORM)
- URL Routing
- Template System
- Form Handling
- Security Features
- Scalability
# MVT
- Model => The data we want to present, usually data from a `database`
- View => A request handler that returns the relevant template and content - based on the request from the user.
- Template => It represents how data should be presented to the application user. It may consist of HTML, CSS, and JS mixed with Django Template language.
# What is a virtual environment
- A virtual environment is a tool that helps to keep dependencies required by different projects separated by creating isolated Python virtual environments for them.
# Steps to install virtual environment
- Step 1 install  => pip install virtualenv
- Step 2: test installation => virtualenv --version
- step 3: naming virtual environment => virtualenv my_env
- step 4: activating virtual env => source ./my_env/Scripts/activate
- step 5: deactivating virtual env => my_env/Scripts>deavtivate

# Installing Django
- python -m pip install django
- Django-admin start project "name"
# Project folder structure
- `__init__.py` The folder which contains __init__.py file is considered as python package
- `wsgi.py` WSGI (Web Server Gateway Interface) is a specification that describes how a web server communicates with web applications, synchronously.
- `asgi.py` Asynchronous Server Gateway Interface. ASGI provides standards for both asynchronous and synchronous
- `settings.py` This file contains all the information or data about project settings. E.g. Database configuration information, template, Installed Application, Validators, etc.
- `urls.py` contains information of URL attached to the application
- `manage.py` manage.py is a project-specific command-line utility
