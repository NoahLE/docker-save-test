# docker-save-test

Testing out some of Docker's commands

## Setup

1. Install Python 3.X

2. Install `virtualenv virtualenv-wrapper`

3. Install requirements

```python
pip install -r requirements.txt
```

4. Make a PostgreSQL database and update the settings file

5. Migrate and run

```python
python manage.py migrate
python manage.py runserver
```