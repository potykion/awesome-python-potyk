# awesome-python-potyk

There are a lot of similar lists, but I want to create my own list to remember which tools I have used or am interested in.

## Similar lists

- https://github.com/vinta/awesome-python
- https://github.com/uhub/awesome-python
- https://github.com/dylanhogg/awesome-python

## Dataclasses 

Tools to write classes without boilerplate (like magic methods for hashing, comparison)

- [dataclasses](https://docs.python.org/3/library/dataclasses.html) - Python built-in dataclasses
- [attrs](https://www.attrs.org/en/stable/) - Python 2 compatible dataclasses
- [pydantic](https://docs.pydantic.dev/latest/) - best lib to write dataclasses which automatically converts raw data to typed data (like converting strings to integers)

## Serialization 

Tools that convert Python data types to text types like JSON, XML, etc.

- [cattrs](https://catt.rs/en/stable/) - serialization for attrs-classes
- [pydantic](https://docs.pydantic.dev/latest/) - builtin serialization
- [xmltodict](https://github.com/martinblech/xmltodict) - convert XML to Python dict
- [lxml](https://lxml.de/) - low-level xml parsing

## Linting 

Tools that analyze and check your code

- [mypy](https://mypy-lang.org/) - most popular type annotated Python code checker
- [ruff](https://beta.ruff.rs/docs/) - fastest linter that checks things like unused imports, pep8 violations
- [black](https://black.readthedocs.io/en/stable/) - best code formatter

## Web Frameworks

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

## Networking (HTTP clients)

- [requests](https://requests.readthedocs.io/en/latest/) - most popular Python HTTP client
- [httpx](https://www.python-httpx.org/) - modern Python HTTP client with async support

## Security

- [pyjwt](https://pyjwt.readthedocs.io/en/stable/) - generate and decode JWT in Python

## Utils 

- [more-itertools](https://pypi.org/project/more-itertools/) - itertools extensions - bunch of reusable functions for collection manipulations
- [python-dateutil](https://pypi.org/project/python-dateutil/) - good for date operations like parsing, finding difference, finding end of month, etc.
- [pyhumps](https://pypi.org/project/pyhumps/) - converts from different cases like from camelCase to snake_case and vice versa
- [Unidecode](https://pypi.org/project/Unidecode/) - transliterate strings from other languages to English

## Work with files 

Tools for working with files like Excel, PDF, Word, images

- [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - best lib to work with Excel files
- [Pillow](https://pillow.readthedocs.io/en/stable/) - most popular lib to work with images

## Other 

- [psutil](https://pypi.org/project/psutil/) - tool for getting machine metrics like memory and cpu usage
