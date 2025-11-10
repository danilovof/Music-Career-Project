Music Career - progetto Django

Passi per eseguire l'applicativo su Windows 10/11:
1. python -m venv venv
2. .\venv\Scripts\activate
3. pip install -r requirements.txt
4. python manage.py makemigrations
5. python manage.py migrate
6. python setup_sample.py   # crea account manager1/artist1 e dati di esempio
7. python manage.py runserver

accounts campioni generati con setup_sample.py:
- manager1 / managerpass
- artist1 / artistpass
