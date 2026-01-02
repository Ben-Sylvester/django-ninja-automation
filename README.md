# django-ninja-kit — A plug-and-play developer toolkit for Django Ninja that auto-wires apps, scaffolds service layers, enforces a standard folder structure, and integrates dependency injection super easily.

Zero-configuration automation for Django Ninja.
Configure once, write APIs, and everything else is wired for you.

## Features

- Auto-wired Ninja API with dependency injection
- Core services, responses, pagination, middleware
- Modular apps structure
- Enterprise-ready project template
- Plug-and-play

## Usage

```bash
pip install django-ninja-kit
ninja-init start myproject
cd myproject
python manage.py runserver

# Install the django-ninja-kit in your settings.py

INSTALLED_APPS = [
    ...
    "django_ninja_kit",
]


