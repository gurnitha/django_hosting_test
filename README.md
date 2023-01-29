# django_hosting_test
Testing a newly created django project to deploy to Gigital Ocean
Github: https://github.com/gurnitha/django_hosting_test


## 01. Setup


#### 01.1 Create django project called 'config'

        modified:   .gitignore
        modified:   README.md
        new file:   config/__init__.py
        new file:   config/asgi.py
        new file:   config/settings.py
        new file:   config/urls.py
        new file:   config/wsgi.py
        new file:   manage.py
        new file:   requirements.txt

        NOTE: 

        Testing: it works


#### 01.2. Preparing project do be deployed to DO

        modified:   README.md
        modified:   config/settings.py

        NOTE:

        1. Install this:

        pip install django gunicorn psycopg2-binary dj-database-url

        2. Modified settings.py file

        3. Testing: Error

        File "F:\_workspace2023\hosting_test\django_hosting_test\config\settings.py", line 103, in <module>
        raise Exception("DATABASE_URL environment variable not defined")
        Exception: DATABASE_URL environment variable not defined

        4. The DO's instructions just push it to Github