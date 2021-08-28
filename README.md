# Описание
API для социальной сети YaTube

# Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```sh
https://github.com/wwwwwdy/api_final_yatube.git
```
```sh
cd api_final_yatube
```
Cоздать и активировать виртуальное окружение:
```sh
python3 -m venv env
```
```sh
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```sh
python3 -m pip install --upgrade pip
```
```sh
pip install -r requirements.txt
```
Выполнить миграции:
```sh
python3 manage.py migrate
```
Запустить проект:
```sh
python3 manage.py runserver
```

# Документация
Документация для проекта:
```sh
http://127.0.0.1:8000/redoc/
```



