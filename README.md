# Assignment-4

### Installation
PyPl
``` bash 
pip install flask
pip install flask-sqlalchemy
pip install bs4
pip install requests
```

### Usage
```bash
from flask import Flask, render_template, request, redirect
from flask_sqlalchemy import SQLAlchemy
import requests
from bs4 import BeautifulSoup
from sqlalchemy import desc
```

### connect to DataBase
```bash
app = Flask(__name__)
app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresqlpostgresPASSWORD@localhostCoinMarket'
db = SQLAlchemy(app)


postgresqluserpasswoed@localhostmydatabase
mysqluserpasswoed@localhostmydatabase
oracleuserpasswoed@127.0.0.11521mydatabase
```


### Examples
```bash
httpsgithub.comselfedu-rusflsite_sqlalchemy-23
httpswww.section.ioengineering-educationflask-database-integration-with-sqlalchemy
```

### Sources
```bash
pyjwt (httpspyjwt.readthedocs.ioenstable)
flask (httpsflask.palletsprojects.comen2.0.x)
flask_sqlalchemy (httpsflask-sqlalchemy.palletsprojects.comen2.x)
requests  (httpspypi.orgprojectrequests)
beautifulSoup (httpswww.crummy.comsoftwareBeautifulSoupbs4doc)
