# Dev-Track
Create a dev tracker of issues like Jira board


# Create project setup

python -m venv .venv 
.venv\Scripts\activate
pip install django
pip install djangorestframework

django-admin startproject config .
python manage.py startapp issues


python manage.py migrate
python manage.py runserver

pip freeze > requirements.txt


