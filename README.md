# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone https://github.com/CodeSode10/django-Bloggingrestapi.py

Now change directory to:

    $ cd django-Bloggingrestapi.py
    $ cd BloggingProject
    
Activate the virtualenv for your project.
    
Install project dependencies:

    $ pip3 install -r requirements/local.txt 
    
Then simply apply the migrations:

    $ python manage.py makemigrations    
    $ python manage.py migrate
    
Or if facing any issue with above use this command instead :

    $ python manage.py migrate --syncdb

You can now run the development server:

    $ python manage.py runserver