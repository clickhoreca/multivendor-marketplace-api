# multi vendor marketplace api

- django
- django rest

## command structure

```
docker-compose run --rm app sh -c "python manage.py runserver"
```

- docker-compose runs a Docker compose command
- run will start a specific container defined in config
- --rm remove the container
- app is the name od the service
- sh -c passes in a shell command
- on " " command to run inside the container

## linter

```
docker-compose run --rm app sh -c "flake8"
```

## test

- django test suite

```
docker-compose run --rm app sh -c "python manage.py test"
```
