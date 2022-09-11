# Cookie Stand API Project

This is a Django project that is based on a (Codefellows Template)[https://github.com/codefellows/python-401-api-quickstart], uses ElephantSQL for a PostgresSQL database and will be deployed using Digital Ocean.

## API-Quick-Start (Template Guide)

Template Project for starting up CRUD API with Django Rest Framework

## Customization Steps

- DO NOT migrate yet
- add additional dependencies as needed
  - Re-export requirements.txt as needed
- change `things` folder to the app name of your choice
- Search through entire code base to `Thing`-> `CookieStand`, and `things`->`cookie_stands` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - App's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
    - `permissions.py`
- Update ThingModel->CookieStandModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- Rename `project/.env.sample` to `.env` and update as needed
- Run makemigrations and migrate commands
- Run `collectstatic` if needed.
- Optional: Update `api_tester.py`
