## django 튜토리얼

### 디렉토리 구조
```zsh
└── django-project
    ├── README.md
    └── django
        ├── db.sqlite3
        ├── manage.py
        ├── mysite
        │   ├── __init__.py
        │   ├── __pycache__
        │   ├── asgi.py
        │   ├── settings.py
        │   ├── urls.py
        │   └── wsgi.py
        └── polls
            ├── __init__.py
            ├── __pycache__
            ├── admin.py
            ├── apps.py
            ├── migrations
            ├── models.py
            ├── templates
            ├── tests.py
            ├── urls.py
            └── views.py
```

### polls 페이지
```
http://3.36.237.198:8000/polls
```

### polls/id 페이지
```
http://3.36.237.198:8000/polls/1/
```

### results 페이지
```
http://3.36.237.198:8000/polls/1/results
```

### admin 페이지
```
http://3.36.237.198:8000/admin
```