Стек технологий:

Python 3.8
Django 2.2
Pytest
SQLite3
CSS
HTML


Установка проекта из репозитория (Linux и macOS)

Клонировать репозиторий и перейти в него в командной строке:
git clone https://github.com/NazLun/yandex_project

cd YaTube

Cоздать и активировать виртуальное окружение:
python3 -m venv venv

source venv/bin/activate
Установить зависимости из файла requirements.txt:

python3 -m pip install --upgrade pip
pip install -r requirements.txt

Выполнить миграции:
python3 manage.py migrate

Запустить проект (в режиме сервера Django):
python3 manage.py runserver

