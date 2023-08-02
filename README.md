# djangosessionauth
Django REST Framework Complete Session Authentication API

## To Run this Project follow below:

```bash
mkvirtualenv venv
venv\scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

## Command to Run Tests:

```bash
python manage.py test
```

#### There is a File "sessionauth.postman_collection" which has Postman Collection You can import this file in your postman to test this API
## Run Tests with Coverage:Run Tests with Coverage:

```bash
coverage run --source='account' manage.py test 
coverage report
```
### HTML Coverage Report (Optional):
```bash
coverage html
```

#### There is a File "sessionauth.postman_collection" which has Postman Collection You can import this file in your postman to test this API
