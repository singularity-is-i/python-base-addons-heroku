# Python addon sample for Heroku


## Running Locally


```sh
$ pip install -r requirements.txt
$ createdb python_getting_started
$ heroku local:run python manage.py migrate
$ python manage.py collectstatic
$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ git push heroku master
$ heroku run python manage.py migrate
```

## Documentation

For more information about using Python on Heroku, see these Dev Center articles:

- [Python with Django on Heroku](https://devcenter.heroku.com/articles/getting-started-with-python#introduction)
- [Deploying Django App on Heroku](https://devcenter.heroku.com/articles/deploying-python)

