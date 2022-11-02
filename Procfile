web: gunicorn fulleffectapi.wsgi
release: python manage.py makemigrations --noinput 
release: python manage.py collectstatic --noinput  
release: python manage.py migrate --noinput
