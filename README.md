### API final Yatube

Благодаря этому проекту через API можно опубликовать свой личный дневник, поделиться мыслями на самые разные темы, почитать публикации других авторов, оставить комментарий на прочитанную публикацию, подписаться на авторов понравившихся постов.

## Технологии

Python 3.7

Django 2.2.19

## Requirements
- Django==2.2.16
- pytest==6.2.4
- pytest-pythonpath==0.7.3
- pytest-django==4.4.0
- djangorestframework==3.12.4
- djangorestframework-simplejwt==4.7.2
- Pillow==8.3.1
- PyJWT==2.1.0
- requests==2.26.0
- djoser==2.1.0

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```

git clone git@github.com:GriMary5566/api_final_yatube.git

```

```

cd api_final_yatube/

```

  

  

Cоздать и активировать виртуальное окружение:

  

  

```

python3 -m venv venv

```

  

```

source venv/bin/activate

```

  

```

python3 -m pip install --upgrade pip

```

  

  

Установить зависимости из файла requirements.txt:

  

  

```

pip install -r requirements.txt

```

  

  

Перейти в папку yatube_api:

  

  

```

cd yatube_api/

```

  

  

Выполнить миграции:

  

  

```

python3 manage.py migrate

```
  

  

Запустить проект:

  

  

```

python3 manage.py runserver

```

  

По адресу `http://127.0.0.1:8000/redoc/` будет доступна документация для API **Yatube**

## Авторы

- Команда Яндекс.Практикума
- Григорьева Мария