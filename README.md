Тестовый проект
Подготовка окружения
Склонируйте репозиторий:

git clone git@github.com:Magaboss/UpTrader-Test.git
Перейдите в папку и активируйте виртуальное окружение:

cd Project_Test/
python -m pip install --upgrade pip
python -m venv venv
venv\Scripts\activate.bat - для Windows;
source venv/Scripts/activate - для MacOS и Linux
Установите необходимые зависимости проекта:

pip install -r requirements.txt
Выполните миграции:

cd menu
python manage.py makemigrations
python manage.py migrate
Запустите проект:

python manage.py runserver
