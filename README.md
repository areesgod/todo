# django-todo
A simple todo-list app built with django

### Setup

You need to install django,in order to do that run in command prompt or editor terminal 
```bash $pip install django```
After installing django,create your project by command
```bash $django-admin startproject 'projectname'```
Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```
Next step to create super user
```bash
$ python manage.py createsuperuser
```
After everything is done,to run server run this command
```bash
$ python manage.py runserver
```
Once the server is hosted, you can access it by 127.0.0.1:8000

