# My First Django App

This is my follow up from the [django tutorials](https://docs.djangoproject.com/en/5.2/intro/).

# Requirements

* Python 3.13
* Django 5.2.2

# Installation

1. To create changes from the model:
    ```
    python manage.py makemigrations
    ```
    * To preview sql migrations, run:
    ```
    python manage.py sqlmigrate polls 0001
    ```
2. To apply changes to the database:

```
python manage.py migrate
```

3. Create an admin

```
python manage.py createsuperuser
```

4. Access teh django shell:

```
python manage.py shell

```

## Running tests

```
python manage.py test polls

```
