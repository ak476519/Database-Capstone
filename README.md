# Database-Capstone

## Setup Guide
Create a Python virtual environment for Django
```shell script
python3 -m venv django
source django/bin/activate
```
Install Django
```shell script
pip install -U pip
python -m pip install Django
```
Verify by invoking the `main_store` endpoint
```python
cd erika_fashion
python manage.py runserver
```
Then visit localhost:8080/main_store

You should see a hello message.