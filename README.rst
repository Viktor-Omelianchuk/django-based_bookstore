Django-based_bookstore
============

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
     :target: https://github.com/ambv/black
     :alt: Black code style


:License: MIT


.. contents::

Website
-------------------

- https://immense-earth-30847.herokuapp.com/


Installation
-------------------
On Unix, Linux, BSD, macOS, and Cygwin::

  $ git clone https://github.com/Viktor-Omelianchuk/django-based_bookstore.git

Create and activate isolated Python environments
-------------------------------------------------
::

    $ cd django-based_bookstore
    $ virtualenv env
    $ source env/bin/activate

Install requirements
--------------------------------------
::

    $ pip install -r requirements.txt

Run local development server
--------------------------------------
::

    $ docker-compose up -d --build

Make migrations
--------------------------------------
::

    $ docker-compose exec web python manage.py migrate

Create superuser
--------------------------------------
::

    $ docker-compose exec web python manage.py createsuperuser


Run tests
-------------------
::

    $ docker-compose exec web python manage.py test

Stop local development server
---------------------------------------------------------
::

    $ docker-compose down

