# Complete Django Girls Tutorial

This repository contains the code that one would eventually have were they to go through the [Django Girls tutorial](https://tutorial.djangogirls.org/en/).

## Differences

Expressing my authorial rights, some things are a bit different from the tutorial:

- A `Log in` and `Log out` links on the page header
- A `Back` link within the *blog-detail* and *blog-edit* pages
- A more extensive `.gitignore` file
- A `.editorconfig` file
- An additional python package in the requirements.txt: `pycodestyle`

- Within `mysite/settings.py`,

  - Use of `Africa/Nairobi` as my *TIME_ZONE*
  - Use of `en-us` as my *LANGUAGE_CODE*
  - Addition of `0.0.0.0` and `.herokuapp.com` to the *ALLOWED_HOSTS* list

## Setup

In a python virtual environment, run:

- `pip install -r requirements.txt`
- `python manage.py migrate blog`
- `python manage.py createsuperuser` (to create user that you'll use to log in)
- `python manage.py runserver`

Now, you are good to go. Your blog is ready.
