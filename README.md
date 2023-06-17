# pythonDjango

python django tutorial for absolute beginners (me)

this is a personal note on how to pretty much install django

1. run venv
2. NOTE: keep venv folder and program folder separate
3. install django (pip install django)
4. start django, initialize (django-admin startproject "foldername") "foldername is djangoProject1 in this case"
5. runserver with manage.py (python "manage.py location (/foldername/manage.py usually" runserver) NOTE: pay attention to where you execute the command in
6. terminal, it will help further development if you continue inside the project folder
7. server runs in localhost, http at the moment by default (http://127.0.0.1:8000/)
8. ctrl + C to stop server
9. NOTE: dont forget pip freeze > requirements.txt later coz github ignores venv folder
10. NOTE: to host add the server's ip to ALLOWED_HOST in settings.py file in the project's folder, currently works just find on ipv4, havent tried ipv6 yet
11. created first test App in same directory as manage.py so it is its own module rather than the djangoProject1's module (python manage.py startapp "appname") "appname is djangoApp1 in this case"
12. created urls.py in App folder and configured urls.py in Project
13. html opened with http://127.0.0.1:8000/App1/
14. to use another database, install respective database bindings and change NAME and ENGINE settings in settings.py, such as 'django.db.backends.sqlite3', 'django.db.backends.postgresql', 'django.db.backends.mysql', or 'django.db.backends.oracle'.
15. NOTE: more references to this at https://docs.djangoproject.com/en/4.2/ref/databases/
16. sql part was a bit confusing, pretty sure there was insert to sqlite but im not sure what timezone has to do with that on the tutorial
17. created user username: admin password: test for createsuperuser, can access admin now
18. END
