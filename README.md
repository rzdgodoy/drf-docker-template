# Django Rest Framework - Project with Docker Template

A simple template for a Django Rest Framework project, using postgres as DB, all based on docker.

1. Create your django app using the following command.

```bash
     docker-compose run app sh -c "django-admin.py startproject app ."
```

2. Then you can create your modules using

```bash
     docker-compose run app sh -c "python manage.py startapp core"
```

3. And finally, when ready, you can test your app using:

```bash  
     docker-compose run app sh -c "python manage.py test && flake8"
```


4. To start your container just:

```bash 
     docker-compose up
```
