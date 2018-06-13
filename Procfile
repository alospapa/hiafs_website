web: gunicorn config.wsgi:application
worker: celery worker --app=hiafs_website.taskapp --loglevel=info
