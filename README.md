# Flask
https://flask.palletsprojects.com/en/3.0.x/  

## First Flask webapp
venv
```
py -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
flask --app nomefile run
``` 
se app.py no --app
flask run --host=0.0.0.0

flask run --debug

### HTML Escaping
return f"Hello, {escape(name)}!"

### Routing
```
@app.route('/')
def index():
    return 'Index Page'

@app.route('/hello')
def hello():
    return 'Hello, World'

```
### WebApps con Flask
https://flask.palletsprojects.com/en/3.0.x/quickstart/
Flask Templates
Flask Forms
HTTP Requests

## Database
Flask SQLAlchemy
https://flask-sqlalchemy.palletsprojects.com/en/3.1.x/quickstart/

Databases Reading, Updating and Deleting CRUD

API



HEROKU O VERCEL Deploying a Flask App

Altro:
Introduction to Authentication with Flask

- wtform

- flask-wtf
https://flask-wtf.readthedocs.io/en/1.2.x/

flask-jwt
flask-migrate
flask-restful



