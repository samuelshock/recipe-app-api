# recipe-app-api

Recipe API project

## running the flake8

To run flake8 into docker container run the followed command:

> docker-compose run --rm app sh -c "flake8"

## running the test into container

To run the test into a container run the followed command:

> docker-compose run --rm app sh -c "python manage.py test"

## creating a Django project

runt the followed command:

> docker-compose run --rm app sh -c "django-admin startproject app ."

## run the server

To run the server run the followed command:

> docker-compose up -d
