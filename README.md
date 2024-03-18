1.actualizar la version de pip install -r requirements.txt
2.configurar la base de datos en settings y crear la base de datos en mysql
3.ejecutar pip install mysqlclient
3.1. crear el super usuario   python manage.py createsuperuser
4. hacer python manage.py makemigrations --el fichero donde esten los modelos de las tablas de BD--
5. hacer un python manage.py migrate
