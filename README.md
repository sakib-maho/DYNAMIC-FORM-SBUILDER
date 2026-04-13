# Dynamic Form Builder

<!-- BrandCloud:readme-standard -->
[![Maintained](https://img.shields.io/badge/Maintained-yes-brightgreen.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Showcase](https://img.shields.io/badge/Portfolio-Showcase-blue.svg)](#)

_Part of the `sakib-maho` project showcase series with consistent documentation and quality standards._

A Django-based web application for building custom forms from the UI and collecting submitted responses in tabular report views.

## Features

- Create forms dynamically from the browser
- Add multiple field types:
  - text
  - number
  - date
  - text area
- Render generated forms instantly
- Submit response entries and view report tables per form
- Simple in-memory prototype for learning and demo purposes

## Quick Start

```bash
git clone https://github.com/sakib-maho/DYNAMIC-FORM-SBUILDER.git
cd DYNAMIC-FORM-SBUILDER
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open `http://127.0.0.1:8000/`.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

## Tech Stack

- Python
- Django 3.2
- HTML + Semantic UI
- JavaScript + jQuery (frontend interactions)

## How to Use

1. Open **Generate Form**
2. Set a form name
3. Add fields using the field buttons
4. Click **Generate**
5. Open the form from **Home**
6. Submit entries and view **Reports**

## Project Structure

- `manage.py` - Django management entrypoint
- `project1/` - Django project settings, routes, and views
- `templates/project1/` - UI templates

## Notes

- Data is stored in process memory in the current implementation.
- Restarting the server clears created forms and submitted responses.
- This repository is best treated as a prototype/demo project.
