# Profiles REST API

## Overview

This REST API is part of the a [django masterclass](https://www.udemy.com/course/django-python/) from Udemy.

## Learning goals of the course:

- How to create a local development server using Vagrant
- How to build a browsable, sel documenting REST API
- How to create a Django project with sqlite db
- How to handle registration, login, and status updates within a Django REST API

## Build

- Start your vagrant vm `vagrant up`
- Access your dev server `vagrant ssh`
- Start virtual environment `ource .venv/bin/activate` (exit with _deactivate_)
- Install libs `pip install -r requirements.txt`
- Run server `python manage.py runserver 0.0.0.0:8000` (server will start on localhost:8000)

## Requirements

- [VirtualBox](https://www.virtualbox.org/wiki/Documentation)
- [Vagrant](https://developer.hashicorp.com/vagrant/docs)
- [Python 3](https://docs.python.org/3/)
- [Django REST Framework](https://www.django-rest-framework.org/#)
