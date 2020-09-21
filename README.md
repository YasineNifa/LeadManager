# LeadManager
- Add leads with name, emails and some other informations
- Authentification
- Login logout
- Each user will have their own leads
- if I create a lead as one user and then login as another I won't be able to see or manage the other's person lead
- To learn Django and React
- some documentation : 
  - `https://www.django-rest-framework.org/`
  - `https://www.valentinog.com/blog/drf/#Django_REST_with_React_Django_and_React_together`
  - `http://v1k45.com/blog/modern-django-part-1-setting-up-django-and-react/`
  
- Make sure, you have Python3 install
- Install pipenv : `pip install pipenv`
- `pipenv shell` to open a virtual environment for our project
- Install some packages `pipenv install django djangorestframework django-rest-knox`
- Create a django project `django-admin startproject leadmanager`
- Create an app `python manage.py startapp leads`
- Add the name of the app in the settings file of our project
- Go to the leads folder, then the models.py file and create a model name Lead
- Once created go to the terminal and execute `python manage.py makemigrations leads` then `python manage.py migrate`
- Let s now go to the API : REST FRAMEWORK
- First we create a serializer.py file in the leads folder. It is a file that will allows complex data such as queryset and models instances to be converted to Python data type that can be easily rendered to JSON, XML AND OTHER ....
- Then we must create api.py file that use viewset that allows us to create a full crud api (create read update and delete) without having to specify explicit methods for the functionality. It is kind like how ruby works


