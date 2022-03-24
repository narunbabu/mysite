django-admin startproject mysite
cd mysite
python manage.py runserver
mkdir static
mkdir templates
python manage.py startapp marcador

python manage.py runserver

python manage.py makemigrations marcador
python manage.py migrate

python manage.py createsuperuser
