# Django REST Framework JWT Example

[![Python Version](https://img.shields.io/badge/python-3.7-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-2.1-brightgreen.svg)](https://djangoproject.com)
[![Django Rest Framework Version](https://img.shields.io/badge/djangorestframework-3.9-brightgreen.svg)](https://www.django-rest-framework.org/)

Code example used in the tutorial [How to Use JWT Authentication with Django REST Framework](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html).

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/sibtc/drf-jwt-example.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Apply the migrations:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The API endpoints will be available at **127.0.0.1:8000/hello/**.


## License

The source code is released under the [MIT License](https://github.com/sibtc/drf-jwt-example/blob/master/LICENSE).
