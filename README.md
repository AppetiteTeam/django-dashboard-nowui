# [Django Dashboard - Now UI Design](https://appseed.us/admin-dashboards/django-dashboard-nowui)

> **Open-Source Admin Dashboard** coded in **Flask Framework** by **AppSeed** [Web App Generator](https://appseed.us/app-generator) - features:

- UI Kit: **[Now UI Dashboard](https://www.creative-tim.com/product/now-ui-dashboard?AFFILIATE=128200)** (Free version) provided by **Creative-Tim**
- UI-Ready app, SQLite Database, Django Native ORM
- Modular design, clean code-base
- Session-Based Authentication, Forms validation
- Deployment scripts: Docker, Gunicorn / Nginx
- **MIT License**
- Free support via **Github** 
- Paid Support **24/7 LIVE Support** via [Discord](https://discord.gg/fZC6hup)

> Links

- [Django Dashboard - Now UI Design](https://appseed.us/admin-dashboards/django-dashboard-nowui) - product page 
- [Django Dashboard Now UI Demo](https://django-dashboard-nowui.appseed.us/login/) - LIVE App
- [Django Dashboard Now UI Docs](https://docs.appseed.us/admin-dashboards/django-dashboard-nowui/) - Documentation
- More [Django Dashboards](https://appseed.us/admin-dashboards/django) - index hosted by **AppSeed**
- More [Admin Dashboards](https://appseed.us/admin-dashboards) - index hosted by **AppSeed**

<br />

## Want more? Go PRO!

PRO versions include **Premium UI Kits**, Lifetime updates and **24/7 LIVE Support** (via [Discord](https://discord.gg/fZC6hup)) 

| [Django Gradient PRO](https://appseed.us/admin-dashboards/django-dashboard-gradient-pro) | [Django Dashboard Black PRO](https://appseed.us/admin-dashboards/django-dashboard-black-pro) | [Django Dashboard Argon PRO](https://appseed.us/admin-dashboards/django-dashboard-argon-pro) |
| --- | --- | --- |
| [![Django Gradient PRO](https://raw.githubusercontent.com/app-generator/django-dashboard-gradient-pro/master/media/django-dashboard-gradient-pro-screen.png)](https://appseed.us/admin-dashboards/django-dashboard-gradient-pro) | [![Django Dashboard Black PRO](https://raw.githubusercontent.com/app-generator/django-dashboard-black-pro/master/media/django-dashboard-black-pro-screen.png)](https://appseed.us/admin-dashboards/django-dashboard-black-pro) | [![Django Dashboard Argon PRO](https://raw.githubusercontent.com/app-generator/django-dashboard-argon-pro/master/media/django-dashboard-argon-pro-screen.png)](https://appseed.us/admin-dashboards/django-dashboard-argon-pro)

<br />
<br />

![Django Dashboard NowUI - Open-Source Web App.](https://raw.githubusercontent.com/app-generator/static/master/products/django-dashboard-nowui-screen.png)

<br />

## How to use it

```bash
$ # Get the code
$ git clone https://github.com/app-generator/django-dashboard-nowui.git
$ cd django-dashboard-nowui
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv --no-site-packages env
$ # .\env\Scripts\activate
$ 
$ # Install modules
$ # SQLIte version
$ pip3 install -r requirements.txt
$
$ # Create tables
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
$
$ # Start the app - custom port 
$ # python manage.py runserver 0.0.0.0:<your_port>
$
$ # Access the web app in browser: http://127.0.0.1:8000/
```

<br />

## Deployment

The app is provided with a basic configuration to be executed in [Docker](https://www.docker.com/), [Gunicorn](https://gunicorn.org/), and [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/).

### [Docker](https://www.docker.com/) execution
---

The application can be easily executed in a docker container. The steps:

> Get the code

```bash
$ git clone https://github.com/app-generator/django-dashboard-nowui.git
$ cd django-dashboard-nowui
```

> Start the app in Docker

```bash
$ sudo docker-compose pull && sudo docker-compose build && sudo docker-compose up -d
```

Visit `http://localhost:5005` in your browser. The app should be up & running. 

<br />

### [Gunicorn](https://gunicorn.org/)
---

Gunicorn 'Green Unicorn' is a Python WSGI HTTP Server for UNIX.

> Install using pip

```bash
$ pip install gunicorn
```
> Start the app using gunicorn binary

```bash
$ gunicorn --bind=0.0.0.0:8001 core.wsgi:application
Serving on http://localhost:8001
```

Visit `http://localhost:8001` in your browser. The app should be up & running.

<br />

### [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/)
---

Waitress (Gunicorn equivalent for Windows) is meant to be a production-quality pure-Python WSGI server with very acceptable performance. It has no dependencies except ones that live in the Python standard library.

> Install using pip

```bash
$ pip install waitress
```
> Start the app using [waitress-serve](https://docs.pylonsproject.org/projects/waitress/en/stable/runner.html)

```bash
$ waitress-serve --port=8001 core.wsgi:application
Serving on http://localhost:8001
```

Visit `http://localhost:8001` in your browser. The app should be up & running.

<br />

## Credits & Links

### [Django Admin Dashboards](https://appseed.us/admin-dashboards/django)

Index with UI-ready **admin dashboards** generated by the AppSeed platform in [Django Framework](https://www.djangoproject.com/).
Start fast your next Django project by using functional admin dashboards enhanced with Database, ORM, authentication flow, helpers and deployment scripts.

### What is [Django](https://www.djangoproject.com/)

[Django](https://www.djangoproject.com/) is a Python-based free and open-source web framework, which follows the model-template-view architectural pattern. It is maintained by the Django Software Foundation, an independent organization established as a 501 non-profit. Django's primary goal is to ease the creation of complex, database-driven websites.

### [What is a dashboard](https://en.wikipedia.org/wiki/Dashboard_(business))

A dashboard is a set of pages that are easy to read and offer information to the user in real-time regarding his business. A dashboard usually consists of graphical representations of the current status and trends within an organization. Having a well-designed dashboard will give you the possibility to act and make informed decisions based on the data that your business provides - *definition provided by [Creative-Tim - Free Dashboard Templates](https://www.creative-tim.com/blog/web-design/free-dashboard-templates/?ref=appseed)*.

### [Now UI Dashboard](https://www.creative-tim.com/product/now-ui-dashboard?AFFILIATE=128200)

**[Now UI Dashboard](https://www.creative-tim.com/product/now-ui-dashboard?AFFILIATE=128200)** is a responsive Bootstrap 4 kit provided for free by Invision and Creative Tim. It combines colors that are easy on the eye, spacious cards, beautiful typography, and graphics. It is light and easy to use, and also very powerful - provided by **Creative-Tim**.

<br />

---
[Django Dashboard - Now UI Design](https://appseed.us/admin-dashboards/django-dashboard-nowui) - Provided by **AppSeed** [Web App Generator](https://appseed.us/app-generator).
