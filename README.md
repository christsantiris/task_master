## set up environment and run project:
```pip3 install virtualenv
virtualenv env
source env/bin/activate
pip3 install flask flask-sqlalchemy

## to run the app in development mode:
python3 app.py

## to set up db: 
in terminal run python3
from app import db
db.create_all()

## to deploy: 
pip3 install gunicorn
pip freeze > requirements.txt 
heroku create crudtaskmaster
git push heroku master


https://crudtaskmaster.herokuapp.com/
