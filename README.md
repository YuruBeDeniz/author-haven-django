# steps

### create a virtual env
python3 -m venv venv

### activate a virtual env
source venv/bin/activate

### inside venv create gitignore
npx gitignore python # author-haven-django

### install requirements
pip install -r requirements/local.txt

pip list

### create the project
django-admin startproject authors_api .

### create secret key
python -c "import secrets; print(secrets.token_urlsafe(38))"

### create users
python manage.py startapp users
python manage.py startapp users
python manage.py startapp users

### run server
python manage.py runserver
