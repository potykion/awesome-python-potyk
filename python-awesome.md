# Awesome Python

**Table of Contents**

<!-- TOC -->
* [Awesome Python](#awesome-python)
  * [Similar lists](#similar-lists)
  * [Dataclasses](#dataclasses)
  * [Web Frameworks](#web-frameworks)
    * [Flask](#flask)
    * [Django](#django)
  * [Databases](#databases)
  * [Networking (HTTP clients)](#networking-http-clients)
  * [Security & DevOps](#security--devops)
  * [Utils](#utils)
  * [Work with files](#work-with-files)
    * [Excel (.xlsx)](#excel-xlsx)
    * [Word (.docx)](#word-docx)
    * [PDF](#pdf)
    * [Images](#images)
  * [Parsing & Scrapping](#parsing--scrapping)
  * [Other](#other)
  * [SDK / API wrappers](#sdk--api-wrappers)
  * [Linting](#linting)
  * [Testing](#testing)
    * [Mocking](#mocking)
    * [pytest](#pytest)
  * [Documentation](#documentation)
  * [Videos](#videos)
    * [Russian](#russian)
<!-- TOC -->

## Similar lists

- https://github.com/vinta/awesome-python
- https://github.com/uhub/awesome-python
- https://github.com/dylanhogg/awesome-python

---

## Dataclasses

Tools to write classes without boilerplate (like magic methods for hashing, comparison)

- [dataclasses](https://docs.python.org/3/library/dataclasses.html) - Python built-in dataclasses
- [attrs](https://www.attrs.org/en/stable/) - pre-Python 3.9 dataclasess
    - [cattrs](https://catt.rs/en/stable/) - serialization extension for attrs
- [pydantic](https://docs.pydantic.dev/latest/) - best lib to write dataclasses which automatically converts raw data to typed data (like converting strings to integers)

---

## Web Frameworks

Tools for writing servers

- [Flask](https://flask.palletsprojects.com/en/latest/) - minimal web framework, good for simple web apps or Python 2 apps, however has a lot of plugins
- [Django](https://www.djangoproject.com/) - most popular batteries-included web framework, that loved by it's builtin ORM
- [FastAPI](https://fastapi.tiangolo.com/) - fast and minimal web framework with Pydantic and Swagger integrations, also can be async

### Flask

Favourite Flask plugins

- [flask-babel](https://python-babel.github.io/flask-babel/) - i18n (localization) for flask based on Babel lib
- [flask-cors](https://flask-cors.readthedocs.io/en/latest/) - CORS for flask (nuff said)
- [flask-limiter](https://flask-limiter.readthedocs.io/en/stable/) - rate limiting for flask
- [flask-login](https://flask-login.readthedocs.io/en/latest/) - lib for server side authentication (like with sessions)
- [flasgger](https://github.com/flasgger/flasgger) - best tool to generate Swagger documentaion for Flask

### Django

- [django-cors-headers](https://pypi.org/project/django-cors-headers/) - CORS for Django
- [django-dburl](https://pypi.org/project/dj-database-url/) - parse database settings from database url (useful along with .env)
- [django-ninja](https://django-ninja.rest-framework.com/) - pydantic & swagger integration for django

---

## Databases

- [peewee](https://github.com/coleifer/peewee) - simplest framework agnostic orm
- [sqlalchemy](https://www.sqlalchemy.org/) - powerful framework agnostic database toolkit
- [repka](https://github.com/potykion/repka) - Simple work with db in async style [my proj 🤓]
- [DuckDB](https://duckdb.org/) - tool for analyzing simple data types like json, csv

---

## Networking (HTTP clients)

- [requests](https://requests.readthedocs.io/en/latest/) - most popular Python HTTP client
- [httpx](https://www.python-httpx.org/) - modern Python HTTP client with async support

## Security & DevOps

- [pyjwt](https://pyjwt.readthedocs.io/en/stable/) - generate and decode JWT in Python
- [python-dotenv](https://saurabh-kumar.com/python-dotenv/) - .env file parsing
- [psutil](https://pypi.org/project/psutil/) - tool for getting machine metrics like memory and cpu usage

## Utils

- [more-itertools](https://pypi.org/project/more-itertools/) - itertools extensions - bunch of reusable functions for collection manipulations
- [python-dateutil](https://pypi.org/project/python-dateutil/) - good for date operations like parsing, finding difference, finding end of month, etc.
- [pyhumps](https://pypi.org/project/pyhumps/) - converts from different cases like from camelCase to snake_case and vice versa
- [Unidecode](https://pypi.org/project/Unidecode/) - transliterate strings from other languages to English
- [potyk-lib](https://github.com/potykion/potyk-lib) - Everyday dev utils like date utils, FP utils, collection utils and so on [my proj 🤓]

---

## Work with files

Tools for working with files like Excel, PDF, Word, images

- [potyk-doc](https://github.com/potykion/potyk-doc) - Everything you need to work with documents in Python [my proj 🤓]
- [docci](https://github.com/potykion/docci) - yet another lib to work with docs [my proj 🤓]

### Excel (.xlsx)

- [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - best lib to work with Excel files
- [jinja2xlsx](https://github.com/potykion/jinja2xlsx) - Create xlsx-tables from html-tables [my proj 🤓]
-

### Word (.docx)

- [python-docx](https://python-docx.readthedocs.io/en/latest/) - lib for working with Word docs
- [docxtpl](https://docxtpl.readthedocs.io/en/latest/) - allows to write Jinja syntax in Word docs

### PDF

- [pdfkit](https://pypi.org/project/pdfkit/) - renders pdf from html using wkhtmltopdf
- [PyPDF2](https://pypdf2.readthedocs.io/en/3.0.0/) - parse pdf info like pages amount

### Images

- [Pillow](https://pillow.readthedocs.io/en/stable/) - most popular lib to work with images

## Parsing & Scrapping

- [requests-html](https://requests.readthedocs.io/projects/requests-html/en/latest/) - lib for HTML parsing based on requests
- [helium](https://github.com/mherrmann/selenium-python-helium) - easier Selenium wrapper which automates browser for testing and scrapping
- [parse](https://pypi.org/project/parse/) - parse strings like with regex but better
- [python-dateutil](https://pypi.org/project/python-dateutil/) - good for date operations like parsing, finding difference, finding end of month, etc.
- [phonenumbers](https://pypi.org/project/phonenumbers/) - phone parsing
- [xmltodict](https://github.com/martinblech/xmltodict) - convert XML to Python dict
- [lxml](https://lxml.de/) - low-level xml parsing

## Other

- [tqdm](https://github.com/tqdm/tqdm) - beautiful progressbar

## SDK / API wrappers

- [potyk-yc](https://github.com/potykion/potyk-yc) - utils and typings for Yandex Cloud [my proj 🤓]

---

## Linting

Tools that analyze and check your code

- [mypy](https://mypy-lang.org/) - most popular type annotated Python code checker
- [black](https://black.readthedocs.io/en/stable/) - best code formatter with PyCharm support
- [ruff](https://beta.ruff.rs/docs/) - fastest linter that checks things like unused imports, pep8 violations
    - UPD: now supports code formatting with black compatibility
- [import-linter](https://import-linter.readthedocs.io/en/stable/) - linter to check import order (like when using
  layerered architecture this tool checks that lower layers can't import upper layers)

## Testing

- [pytest](https://docs.pytest.org/en/latest/) - best test runner and framework with variety plugins
- [faker](https://faker.readthedocs.io/en/master/) - fake data generator
- [factoryboy](https://factoryboy.readthedocs.io/en/stable/) - easy complex object creation for tests with faker integration
- [PyHamcrest](https://github.com/hamcrest/PyHamcrest) - useful test matchers like dict has entities

### Mocking

- [mock](https://docs.python.org/3/library/unittest.mock.html) - python builtin mocking
- [freezegun](https://github.com/spulec/freezegun) - date mocking
- [responses](https://github.com/getsentry/responses) - requests mock

### pytest

Favourite pytest plugins

- [pytest_factoryboy](https://pytest-factoryboy.readthedocs.io/en/stable/) - factoryboy integration
- [pytest-snapshot](https://pypi.org/project/pytest-snapshot/) - snapshot testing useful when need to compare large
  files in assertions (supports py2)
- [syrupy](https://github.com/tophat/syrupy) - better snapshot testing lib
- [pytest-env](https://pypi.org/project/pytest-env/) - .env parsing before test run
- [pytest-flask](https://pypi.org/project/pytest-flask/), [pytest-django](https://pytest-django.readthedocs.io/en/latest/) -
  flask / django integrations

## Documentation

- [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) - best markdown documentation tool

---

## Videos

> YouTube channels with Python videos like conference talks

### Russian

- [IT.People](https://www.youtube.com/@videoitpeople) - PyCon Russia and other tech conferences
- [Moscow Python](https://www.youtube.com/@moscowdjangoru) - talks from Moscow Python meetup and other Python stuff like Moscow Python Podcast
- [Moscow Python Conf](https://www.youtube.com/@PythonChannelRussia/featured) - videos from Moscow Python Conf conference
- [Computer Science Center](https://www.youtube.com/@CompscicenterRu/featured) - online university computer science lectures including Python
- [Хитрый Питон](https://www.youtube.com/@user-th6xg5bk4c/featured) - short (~ 10 mins) videos about Python
