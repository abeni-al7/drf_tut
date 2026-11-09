# DRF Snippets (Tutorial, early stage)

An early stage of the official Django REST Framework tutorial: a code-snippet API implemented with plain Django views before ViewSets and routers are introduced.

## Features

- `Snippet` model (code, title, language, style, line numbers)
- `SnippetSerializer` for serialization/deserialization
- CSRF-exempt function views (`snippet_list`, `snippet_detail`) returning `JsonResponse`

## Built with

- Django
- Django REST Framework
- Pygments, HTTPie (dev)
- SQLite

## Run it

Dependencies are managed with Pipenv:

```bash
pipenv install
pipenv run python manage.py migrate
pipenv run python manage.py runserver
```

Tutorial learning project.
