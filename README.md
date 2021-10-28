# Django-Rest-Framework

![1](https://user-images.githubusercontent.com/55083861/139196967-a5378da0-a75f-4832-af8c-b93cd1c71cd8.PNG)


Django REST framework is a powerful and flexible toolkit for building Web APIs.

Some reasons you might want to use REST framework:

The Web browsable API is a huge usability win for your developers.
Authentication policies including packages for OAuth1a and OAuth2.
Serialization that supports both ORM and non-ORM data sources.
Customizable all the way down - just use regular function-based views if you don't need the more powerful features.
Extensive documentation, and great community support.
Used and trusted by internationally recognised companies including Mozilla, Red Hat, Heroku, and Eventbrite.

Requirements
REST framework requires the following:

Python (3.5, 3.6, 3.7, 3.8, 3.9)
Django (2.2, 3.0, 3.1)
We highly recommend and only officially support the latest patch release of each Python and Django series.

The following packages are optional:

PyYAML, uritemplate (5.1+, 3.0.0+) - Schema generation support.
Markdown (3.0.0+) - Markdown support for the browsable API.
Pygments (2.4.0+) - Add syntax highlighting to Markdown processing.
django-filter (1.0.1+) - Filtering support.
django-guardian (1.1.1+) - Object level permissions support.
Installation
Install using pip, including any optional packages you want...

pip install djangorestframework
pip install markdown       # Markdown support for the browsable API.
pip install django-filter  # Filtering support


Bug Solved for mysqlclient

install pymysql ( command - pip install pymsql )

Add this to root level .init file

import pymysql
pymysql.install_as_MySQLdb()



Special thanks to ### Feel Free To Code
