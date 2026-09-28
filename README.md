# Django Commerce Platform

A server-rendered commerce platform with catalog, cart, account, blog, and checkout modules.

## Run locally

```bash
cd main
python -m venv .venv
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Set `DJANGO_SECRET_KEY` for non-local environments.
