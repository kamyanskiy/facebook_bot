# facebook_bot

Flask, SQLAlchemy, Facebook API

cd git repo

```
$ heroku create
https://agile-gorge-62409.herokuapp.com/
```
```
$ git push heroku master
```
```
$ heroku logs -t -a
```
To set vars on heroku:
```
$ heroku config:set TIMES=2
```

Create db on remote machine:
```
heroku run python

>>> from app import db
>>> db.create_all()

```

```
$ heroku pg:psql
```