Стандартная структура папок проекта Django
```
source_code_initial/
│
├── django_celery/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── feedback/
│   │
│   ├── migrations/
│   │   └── __init__.py
│   │
│   ├── templates/
│   │   │
│   │   └── feedback/
│   │       ├── base.html
│   │       ├── feedback.html
│   │       └── success.html
│   │
│   │
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── .gitignore
├── manage.py
└── requirements.txt
```

```bash
python  -m venv .venv
echo "Virtual enviroment create"
source .venv/bin/activate
echo "Virtual enviroment activate"
python manage.py migrate
echo "Create first migration Django"
python manage.py runcerver
echo "Run test server Django"
```

