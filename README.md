# dGen_III


python -m venv venv
venv\Scripts\activate
pip install django psycopg2-binary
django-admin startproject fund_profiles .
python manage.py runserver
python manage.py startapp pages