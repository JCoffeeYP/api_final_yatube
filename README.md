![PyPI - Django Version](https://img.shields.io/pypi/djversions/djangorestframework?label=djangorestframework&style=plastic)

# API для социальной сети YaTube
### Учебный проект по курсу Python-разработчик от Яндекс.Практикума —  API для социальной сети YaTube

## Техническое описание

Technology    | Version
:-----------: | :-----------:
Python        | 3.8.5
Django        | 3.2.3
Django Rest Framework | 3.12.4

## Для запуска проекта на локальной машине требуется выполнить следующие действия
- Склонировать репозиторий `https://github.com/JCoffeeYP/api_final_yatube.git`
- Установить виртуальное окружение `python3.8 -m venv venv`
- Активировать виртуальное окружение `source venv/bin/activate`
- Установить зависимости `pip install --upgrade pip && pip install -r requirements.txt`
- При необходимости создать superuser `python manage.py createsuperuser`
- Запустить проект `python manage.py runserver`

### Все эндпоинты описаны по адресу http://127.0.0.1:8000/redoc