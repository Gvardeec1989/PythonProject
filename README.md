## Приложение: Планировщик задач.

стек (python3.9, Django, Postgres)


### Установка виртуальной среды для проэкта:

1. Создать песочницу: `python3 -m virtualenv env`
2. Войти в виртуальную среду: `source env/bin/activate`
3. Обновить "pip" виртуальной среды: `pip install --upgrade pip`
4. Установить библиотеки проэкта: `pip install -r requirements.txt`


### Запустить проэкт на этом этапе:

1. Войти в папку `cd todolist`
2. Все миграции созданы, осталось их записать в postgres `./manage.py migrate`
3. Запустить сервер `./manage.py runserver`

### Запуск докера

В папке `todolost` запустить команду `sudo docker-compose up`

###CI/CD


Здесь всё автоматически. Запускается через action.yaml
