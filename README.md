Название:
API yamdb_final

Описание:

API проекта Yamdb (социальной сети с возможностью ревью книг/фильмов и других произведений)

Технологии:

Python 3.7.3.
 
Django 3.0.5.

Docker 20.10.7

Полный список используемых технологий см. в requirements.txt

Установка:

Скачать приложение https://github.com/chgala/yamdb_final.git

В корневой папке проекта (для Linux/Mac os):

--- python -m venv venv

--- . venv/bin/activate

--- pip install -r requirements.txt

--- docker-compose up -d --build

--- docker-compose exec web python manage.py migrate --noinput

--- docker-compose exec web python manage.py collectstatic --no-input


