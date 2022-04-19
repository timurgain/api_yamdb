# Yamdb, API-project

## Description

The project collects feedback on various works (music, movies, books), provides endpoints for commenting and rating.
To access the API, the issue of a JWT token is connected. Pagination, throttling, permissions are also configured.

## Technologies

- Python 3;
- Django REST Framework;
- SQLlite.

## Installation and launch

Clone repository and navigate to folder on command line::

```
git clone ...
```

```
cd api_yamdb
```

Create and activate virtual environment:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Install dependencies from requirements.txt file:

```
pip install -r requirements.txt
```

Run migrations:

```
python3 manage.py migrate
```

Launch the project:

```
python3 manage.py runserver
```

[ReDoc](http://127.0.0.1:8000/redoc/)

## The authors:
- [Храповицкий Дмитрий](https://github.com/dimkafaint)
- [Кузнецов Андрей](https://github.com/HoodFast)
- [Гайнутдинов Тимур](https://github.com/timurgain)
