1 . py -m venv .venv create virtual environment
2. cmd => .venv\Scripts\activate.bat => activate virtual environment ARBA source .venv/Scripts/activate
3. py -m pip install Django => install django
4. if message => py -m pip install --upgrade pip => upgrade pip
4.1 py => import django => print(django.get_version()) => quit() / enter python terminal and get what django version installed
5. django-admin startproject backend => start new project
6. go to project folder where is manage.py file and type => py manage.py runserver => to run server

7. py manage.py startapp posts => creates new app in django framework

8. py manage.py migrate => migrate all models
python manage.py createsuperuser
9. py manage.py makemigrations => create migrations for new models 

10. to use Postgres DB need => pip install psycopg2

11. admin panel for django to create super user => py manage.py createsuperuser add user and password

