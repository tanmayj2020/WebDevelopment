This is my first flask project 
A simple TODO application


# SAMPLE VERSION OF TODO APP
This app is written in Python with Flask and SQLAlchemy

## A. Dependency
In order to run this app, the following dependencies must have been already installed:
1. Postgres. 
 * Start manually: `pg_ctl -D /usr/local/var/postgres start`
 * Stop manually: `pg_ctl -D /usr/local/var/postgres stop -s -m fast`
 
2. Flask

python -m pip install -r requirements.txt` to install dependencies. For Mac users, if you face difficulty in installing the `psycopg2`, you may consider intalling the `sudo brew install libpq` before running the `requirement.txt`. 
* `python3 app.py` to run the app (http://127.0.0.1:5000/ or http://localhost:5000)
