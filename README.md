# api-quick-start

Template Project for starting up CRUD API with Django Rest Framework

## Customization Steps

- DO NOT migrate yet
- add additional dependencies as needed
  - Re-export requirements.txt as needed
- change `things` folder to the app name of your choice
- Search through entire code base for `Thing`,`Things` and `things` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - App's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
    - `permissions.py`
- Update ThingModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- Rename `project/.env.sample` to `.env` and update as needed
- Run makemigrations and migrate commands
- Run `collectstatic` if needed.
- Optional: Update `api_tester.py`

![elephantDB](imgs/DB1.png)
![elephantDB2](imgs/DB2.png)

## super users

`username: admin password : mmt12345`

`username: osama password : osamamaher`

## accessable links 
`admin/` to login <br>
`api/v1/cookie_stands/` to check the cookie stands <br>
`api-auth/` <br>
`api/token/` <br>
`api/token/refresh` <br>
