# Dockerized Django project

Free skeleton for Django project, implemented with docker-compose

## Initialize

From terminal run
```bash
$ docker-compose up -d
```

## Run migrations

From terminal run
```bash
$ docker exec -it docker_python_web bash

root@service /code: python manage.py migrate
```

Now you can go to [localhost:8085](http://localhost:8085)
