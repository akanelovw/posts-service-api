# Описание проекта Posts Service Api
API для проекта Posts Service
В проекте Posts Service Api реализована возможность запрашивать данные о постах, группах и комментариях.
Также в проекте реализована возможность создавать новые посты, группы и коментарии обращаясь к API.

## Стек использованных технологий
- Python 3.9
- Django 3.2.16
- Django REST framework 3.12.4

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:ripKrul/api_yatube.git
```

```
cd yatube_api/
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
