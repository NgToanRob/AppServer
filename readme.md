python -m venv flaskEnv

windows: flaskEnv\Scripts\activate

pip install flask flask-sqlalchemy flask-login

set FLASK_APP=project
set FLASK_DEBUG=1

flask run