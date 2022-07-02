# TodoApp

## Getting Started

```bash
python -m virtualenv venv # Create the Virtual Environment
../venv/Scripts/activate # Execute this command inside src (it could change), Activates the Virtual Environment
pip install Django
pip install djangorestframework
pip install django-cors-headers
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Go to `http://localhost:8000/admin` to create some todos, next open `/frontend/index.html` with Live Server and that's it.

Happy Coding!