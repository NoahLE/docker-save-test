# docker-save-test

Testing out some of Docker's commands

## Setup

1. Install Python 3.X and Docker

2. Install `virtualenv virtualenv-wrapper`

3. Install requirements

```python
pip install -r requirements.txt
```

4. Build the Docker container

```bash
docker-compose up
```

5. Migrate and run

```python
docker exec -it <IMAGE_OR_CONTAINER> python manage.py migrate
```