Django Auto REST Project
=======

.. image:: https://travis-ci.org/AlexandreProenca/django-auto-rest-project.svg?branch=master
        :target: https://travis-ci.org/AlexandreProenca/django-auto-rest-project

.. image:: https://img.shields.io/pypi/v/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://img.shields.io/pypi/dd/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://img.shields.io/pypi/pyversions/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://img.shields.io/pypi/l/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://img.shields.io/pypi/wheel/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://img.shields.io/pypi/format/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://img.shields.io/pypi/implementation/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://img.shields.io/pypi/status/django-auto-rest-project.svg
        :target: https://pypi.python.org/pypi/django-auto-rest-project

.. image:: https://api.codacy.com/project/badge/50515222d332430aba11bcbe76706f14
        :target: https://www.codacy.com/app/linuxloco/django-auto-rest-project

.. image:: https://readthedocs.org/projects/django-auto-rest-project/badge/?version=latest
        :target: http://django-auto-rest-project.readthedocs.org/en/latest/
        :alt: Documentation Status

.. image:: http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat
        :target: http://stackshare.io/AlexandreProenca/django-auto-rest-project
        :alt: Documentation Status

.. image:: https://img.shields.io/badge/GITTER-join%20chat-green.svg
        :target: https://gitter.im/AlexandreProenca/devfriends?utm_source=share-link&utm_medium=link&utm_campaign=share-link
        :alt: Chat room



-----------

.. image:: https://img.shields.io/badge/english-ok-green.svg
        :target: https://img.shields.io/badge/english-ok-green.svg
        :alt: Documentation Status

This package aims to facilitate the creation of Django projects with Django Rest Framework

.. image:: https://img.shields.io/badge/portugues--brasil-ok-green.svg
        :target: https://img.shields.io/badge/portugues--brasil-ok-green.svg
        :alt: Documentation Status

Este pacote tem o objectivo de facilitar a criação de projetos Django + Django Rest Framework


    Documentation: http://django-auto-rest-project.readthedocs.org/

Installation
------------
    Easiest and safe way to install this library is by using pip and virtualenv:
    
    $ **virtualenv myenv**
    
    $ **cd myenv**
    
    $ **source bin/activate**
    
    $ **mkdir myproject**
    
    $ **cd myproject**
    
    $ **pip install django-auto-rest-project**


Usage
-----
    usage: robot_rest [-h] [-vv VERBOSE] -ip DATABASE_HOST -user DATABASE_USER -database DATABASE_NAME -password DATABASE_PASSWORD -project PROJECT_NAME

    optional arguments:
    **-h, --help**                  Show this help message and exit
    
    **-vv VERBOSE, --verbose**      VERBOSE Increase verbosity.
    
    **-ip DATABASE_HOST**           Host address of the database
    
    **-user DATABASE_USER**         Username that have access database
    
    **-database DATABASE_NAME**     The name of the database
    
    **-password DATABASE_PASSWORD** Password to access the database
    
    **-project PROJECT_NAME**       The name of the project.
    

Exemples:

    `robot_rest -ip 187.45.196.236 -user nwpartner3 -database partnerdb -project webscrapy -password sdf435*7`

Project Schema
----

    |project_name
    
    ├── core
    
        ├── admin.py
    
        ├── __init__.py
    
        ├── migrations
    
        ├── models.py
    
        ├── serializers.py
    
        ├── tests.py
    
        ├── urls.py
    
        └── views.py
    
    ├── manage.py
    
    └── project_name
    
        ├── __init__.py
    
        ├── settings.py
    
        ├── urls.py
    
        └── wsgi.py

Packages will be install
----
    * cached-property (1.2.0)
    * Django (1.8.4)
    * django-admin-bootstrapped (2.5.5)
    * django-auto-rest-project (0.1.1)
    * django-braces (1.8.1)
    * django-cors-headers (1.1.0)
    * django-drf-file-generator (0.1.0)
    * django-filter (0.11.0)
    * django-jet (0.0.9)
    * django-oauth-toolkit (0.9.0)
    * django-rest-auth (0.5.0)
    * django-rest-swagger (0.3.4)
    * django-url-filter (0.2.0)
    * djangorestframework (3.2.3)
    * enum34 (1.0.4)
    * funcsigs (0.4)
    * Markdown (2.6.2)
    * mock (1.3.0)
    * MySQL-python (1.2.5)
    * oauthlib (1.0.1)
    * pbr (1.7.0)
    * python-memcached (1.57)
    * PyYAML (3.11)
    * setuptools (3.6)
    * simplejson (3.8.0)
    * six (1.9.0)
    * wsgiref (0.1.2)
    * yet-another-django-profiler (1.0.0)

Requirements
^^^^^^^^^^^^
    * Python 2.7, 3.x, pypy or pypy3
    * Django 1.8+ (there are plans to support older Django versions)
    * Django REST Framework 2 or 3


Authors
-------

`django-auto-rest-project` was written by `Alexandre Proença <alexandre.proenca@hotmail.com.br>`_.