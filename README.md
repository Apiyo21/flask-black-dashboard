# [Flask Dashboard - Black Design](https://appseed.us/admin-dashboards/flask-dashboard-black)

> **Open-Source Admin Dashboard** coded in **Flask Framework** by **AppSeed** [Web App Generator](https://appseed.us/app-generator) - Features

- UI Kit: **Black Dashboard** (Free version) provided by **Creative-Tim**
- Modular design with **Blueprints**
- SQLite, PostgreSQL, SQLAlchemy ORM
- Alembic (DB schema migrations)
- Session-Based authentication (via **flask_login**)
- Deployment scripts: Docker, Gunicorn / Nginx
- **MIT License**
- Free support via **Github** 
- Paid Support **24/7 LIVE Support** via [Discord](https://discord.gg/fZC6hup)

> Links

- [Flask Dashboard - Black Design](https://appseed.us/admin-dashboards/flask-dashboard-black) - Product page
- [Flask Dashboard Black Demo](https://flask-dashboard-black.appseed.us/) - LIVE app
- [Flask Dashboard Black Docs](https://docs.appseed.us/admin-dashboards/flask-dashboard-black/) - App Documentation
- More [Flask Dashboards](https://appseed.us/admin-dashboards/flask) - index hosted by **AppSeed**
- More [Admin Dashboards](https://appseed.us/admin-dashboards) - index hosted by **AppSeed**

<br />

## Want more? Go PRO!

PRO versions include **Premium UI Kits**, Lifetime updates and **24/7 LIVE Support** (via [Discord](https://discord.gg/fZC6hup))

| [Flask Dashboard Material PRO](https://appseed.us/admin-dashboards/flask-dashboard-material-pro) | [Flask Dashboard Black PRO](https://appseed.us/admin-dashboards/flask-dashboard-black-pro) | [Flask Dashboard Argon PRO](https://appseed.us/admin-dashboards/flask-dashboard-argon-pro) |
| --- | --- | --- |
| [![Flask Dashboard Material PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-material-pro/master/media/flask-dashboard-material-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-material-pro) | [![Flask Dashboard Black PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-black-pro/master/media/flask-dashboard-black-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-black-pro) | [![Flask Dashboard Argon PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-argon-pro/master/media/flask-dashboard-argon-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-argon-pro)

<br />
<br />

![Flask Dashboard - Black Design, dashboard screen.](https://raw.githubusercontent.com/app-generator/flask-black-dashboard/master/media/flask-black-dashboard-screen.png)

<br />

## How to use it

```bash
$ # Get the code
$ git clone https://github.com/app-generator/flask-black-dashboard.git
$ cd flask-black-dashboard
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv --no-site-packages env
$ # .\env\Scripts\activate
$
$ # Install modules - SQLite Database
$ pip3 install -r requirements.txt
$
$ # OR with PostgreSQL connector
$ # pip install -r requirements-pgsql.txt
$
$ # Set the FLASK_APP environment variable
$ (Unix/Mac) export FLASK_APP=run.py
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
$
$ # Set up the DEBUG environment
$ # (Unix/Mac) export FLASK_ENV=development
$ # (Windows) set FLASK_ENV=development
$ # (Powershell) $env:FLASK_ENV = "development"
$
$ # Start the application (development mode)
$ # --host=0.0.0.0 - expose the app on all network interfaces (default 127.0.0.1)
$ # --port=5000    - specify the app port (default 5000)  
$ flask run --host=0.0.0.0 --port=5000
$
$ # Access the dashboard in browser: http://127.0.0.1:5000/
```

<br />

## Deployment

The app is provided with a basic configuration to be executed in [Docker](https://www.docker.com/), [Gunicorn](https://gunicorn.org/), and [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/).

<br />

### [Docker](https://www.docker.com/) execution
---

The application can be easily executed in a docker container. The steps:

> Get the code

```bash
$ git clone https://github.com/app-generator/flask-black-dashboard.git
$ cd flask-black-dashboard
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
$ gunicorn --bind 0.0.0.0:8001 run:app
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
$ waitress-serve --port=8001 run:app
Serving on http://localhost:8001
```

Visit `http://localhost:8001` in your browser. The app should be up & running.

<br />

## Credits & Links

<br />

### What is [Flask](https://www.palletsprojects.com/p/flask/)

[Flask](https://www.palletsprojects.com/p/flask/) is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around Werkzeug and Jinja and has become one of the most popular Python web application frameworks.

<br />

### [What is a dashboard](https://en.wikipedia.org/wiki/Dashboard_(business))

A dashboard is a set of pages that are easy to read and offer information to the user in real-time regarding his business. A dashboard usually consists of graphical representations of the current status and trends within an organization. Having a well-designed dashboard will give you the possibility to act and make informed decisions based on the data that your business provides - *definition provided by [Creative-Tim - Free Dashboard Templates](https://www.creative-tim.com/blog/web-design/free-dashboard-templates/?AFFILIATE=128200)*.

<br />

### [Black Dashboard](https://www.creative-tim.com/product/black-dashboard?AFFILIATE=128200)

[Black Dashboard](https://www.creative-tim.com/product/black-dashboard?AFFILIATE=128200) is a beautiful Bootstrap 4 Admin Dashboard with a huge number of components built to fit together and look amazing. If you are looking for a tool to manage and visualize data about your business, this dashboard is the thing for you. It combines colors that are easy on the eye, spacious cards, beautiful typography, and graphics.
Black Dashboard comes packed with all plugins that you might need inside a project and documentation on how to get started. It is light and easy to use, and also very powerful.

[Black Dashboard](https://www.creative-tim.com/product/black-dashboard?AFFILIATE=128200) features over 16 individual components, giving you the freedom of choosing and combining. This means that there are thousands of possible combinations. All components can take variations in color, that you can easily modify using SASS files. You will save a lot of time going from prototyping to full-functional code because all elements are implemented.

<br />

---
[Flask Dashboard - Black Design](https://appseed.us/admin-dashboards/flask-dashboard-black) - Provided by **AppSeed** [Web App Generator](https://appseed.us/app-generator).
