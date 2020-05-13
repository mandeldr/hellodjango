# hellodjango
A simple starter project that demonstrates how Django views, templates, and URL patterns work together

conda create -n hellodjango python=3.8\
conda activate hellodjango\
pip install django\
django-admin startproject hellodjango\
python manage.py runserver\
python manage.py startapp homepage\
python manage.py createsuperuser\
python manage.py migrate
