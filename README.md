# Тестовый проект
### Подготовка окружения
Склонируйте репозиторий:
````
git clone https://github.com/Magaboss/UpTrader-Test.git
````
### Перейдите в папку и активируйте виртуальное окружение:

```

 cd Project_Test/
 python -m pip install --upgrade pip
 python -m venv venv
 venv\Scripts\activate.bat - для Windows
 source venv/Scripts/activate - для MacOS и Linux

````
### Выполните миграции:
```
cd src
python manage.py makemigrations
python manage.py migrate

````
### Запустите проект:
```
python manage.py runserver

````
# Готовый суперпользователь 
```
Username: prison
Password : 1111111111
