### Kittygram
## Проект kittygram предназначем для публикации котов. В проекте реализован API с помощью которого можно добавлять котов на сай. Добавлена аутентификация по JWT токену. 
Стек: Python, Django, Django REST Framework, djoser, simpleJWT.

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram2.git
```

```
cd kittygram2
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
