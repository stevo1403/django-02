# Django-02

## Task Title

**Django CRUD**

## Steps taken
* Created a new Django project named `I4G031041SMD`: `django-admin startproject I4G031041SMD`
* Created an application named `blog` inside project `I4G031041SMD`: `python manage.py startapp blog`
* Added model `Post` with `title`, `slug`, `author`, `body`, `publish`, `created`, `updated`, and `status` field in the `blog` app.
* Created migrations for the new model: `python manage.py makemigrations`
* Executed the newly created migrations: `python manage.py migrate`
* Added five(5) views to the `blog` app: `PostListView`, `PostCreateView`, `PostDetailView`, `PostUpdateView`, and `PostDeleteView`
* Mapped routes to their respective views in the `blog` app.
* Included the `blog` route in `urls.py`.

## Technology used
* Python
* Django
* Virtualenv
* Git

## Create and activate virtual environment
* `python -m venv .venv`
* `.venv\Scripts\activate.bat`

## Install the required dependencies
```pip install -r requirements.txt```

## Usage

```python manage.py runserver```