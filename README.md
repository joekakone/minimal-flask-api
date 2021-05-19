# minimal-flask-api
Hello, I'm Joseph Konka, Python enthousiast. In this porject, I'm building a Minimal API with Flask and Deploy it on Heroku. You can see the result [here](https://minimal-flask-api-jk.herokuapp.com)

## Features
1. Build API with Flask
2. Deploy on Heroku

## Setup environment
```sh
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
export FLASK_APP=app
```

## Launch
```sh
python3 app.py
flask run --host=0.0.0.0 --port=5000
gunicorn app:app
```