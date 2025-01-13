release: pip install setuptools==59.5.0 && pip install -r requirements.txt
release: python manage.py makemigrations && python manage.py migrate
web: gunicorn drf_api.wsgi