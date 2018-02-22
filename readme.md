requires mysql database 'todolist'

once set up, ```sudo apt-get install libmysqlclient```, ```pip install mysqlclient```, and ```python manage.py migrate``` to migrate tables

after migration, run ```python manage.py createsuperuser --username=admin --email=fake@noemail.com```
