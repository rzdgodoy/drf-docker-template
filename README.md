# Django Rest Framework - Project with Docker Template

A simple template for a Django Rest Framework project, using postgres as DB, all based on docker.

1. Create your django app using the following command.

  .. code-block:: bash
  
     docker-compose run app sh -c "django-admin.py startproject app ."
     # You might change the project name : "app"

2. Then you can create your modules using

  .. code-block:: bash
  
     docker-compose run app sh -c "python manage.py startapp core"

3. And finally, when ready, you can test your app using:

.. code-block:: bash
  
     docker-compose run app sh -c "python manage.py test && flake8"


4. To start your container just:

.. code-block:: bash
  
     docker-compose up

