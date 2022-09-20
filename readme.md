<!-- Please update value in the {}  -->

<h1 align="center">Django Weather App</h1>


<div align="center">
  <h3>
    <a href="https://github.com/esadakman/django-weather-app">
      Project
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
- [Stack & Tools](#stack)
- [Project Structure](#project-structure)
- [How to use](#how-to-use)
- [Contact](#contact)

<!-- OVERVIEW -->

## Overview

This is a weather app where API requests were made visual using Django. API service used in this is project is from [openweathermap](https://openweathermap.org/)

 ![weather-app](https://user-images.githubusercontent.com/98649983/191217625-68051481-5dee-4b2d-b43d-ec2133a2fb4d.gif)



<h2 id="stack">Stack & Tools</h2>

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- Django
- HTML
- CSS
- JavaScript
- Bootstrap
- Openweathermap API service

## Project Structure

```bash
.──── django-weather-app (repo)
│
├── manage.py
├── db.sqlite3
├── main
│   ├── __init__.py
│   ├── __pycache__
│   └── wsgi.py
│
└── weatherapp
    ├── __init__.py
    ├── __pycache__
    ├── admin.py
    ├── apps.py
    ├── migrations
    ├── models.py
    ├── static
    │   └── weatherapp
    │       ├── css
    │       │   └── main.css
    │       └── js
    │           └── timeout.js
    ├── templates
    │   └── weatherapp
    │       └── index.html
    ├── tests.py
    ├── urls.py
    └── views.py
```


## How To Use

<!-- This is an example, please update according to your application -->

```bash
# Clone this repository
$ git clone https://github.com/esadakman/django-weather-app.git

# Install dependencies
    $ python -m venv env
    > env/Scripts/activate (for win OS)
    $ source env/bin/activate (for macOs/linux OS)
    $ pip install -r requirements.txt

# Add .env file
    add your SECRET_KEY and API_KEY
    
# Run the app
    $ python manage.py runserver

# Get an API key from:
https://openweathermap.org/
```

## Contact 

- Website [@esadakman](https://esadakman.github.io/)
- GitHub [@esadakman](https://github.com/esadakman)
- Linkedin [@esadakman](https://www.linkedin.com/in/esadakman/)