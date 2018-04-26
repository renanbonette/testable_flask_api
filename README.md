# Project Title

API Restful utilizando framework Flask e abordagem TDD


### Prerequisites

```
Python3
Flask
Virtualenv
Postgres
```

```
Flask-API
autoenv
flask
flask-sqlalchemy 
psycopg2==2.7.3.2
flask-migrate
flask_script
```

### Installing

```
Clonar o Repositório
cd testable_flask_api/
virtualenv venv\
source venv/bin/activate
python manage.py db init
createdb test_db
createdb flask_api
python manage.py db migrate
python manage.py db upgrade
pip install -r requirements.txt
Criar o banco 'teste_tbl para rodar os testes
Criar o banco 'falsk_api' para rodar a aplicação
python test_bucketlist.py
python run.py
```