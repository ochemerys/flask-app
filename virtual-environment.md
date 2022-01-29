# Python project virtual environment

create app folder and cd to it

``` 
cd .\flask-app
```

create virtual environment

``` 
py -m venv env
```

activate virtual environment

``` 
env\Scripts\activate
```

set environment variable for flask to run app

``` 
(env) PS C:\flask-app> set FLASK_APP=app.py
```

run app

```
flask run
```

get out of virtual environment

```
deactivate
```
