# Jogging-Tracker

1. Run into python virtual env
C:\Users\messi\Documents> pymote_env\Scripts\activate
2. change your directory to backend
3. Install required libraries
jogging\backed\jogging_tracker>pip install -r requirements.txt
4. Run backend server
jogging\backed\jogging_tracker>.\manage.py runserver

5. Run into python console
jogging\backed\jogging_tracker>manage.py shell
(you can use your python code here.)
>>> from user.models import User
>>> u = User.objects.get(email='admin@example.com')
>>> u.set_password('testtest')
>>> u.save()
>>> exit()

6. CORS permission
jogging\backed\jogging_tracker\jogging_tracker\settings.py
CORS_ORIGIN_WHITELIST = (
    'localhost:3000',
    'localhost:3001',
    'localhost:8000',
    '127.0.0.1:9000'
)
