# myWebproject

This is a personal project based on django framework and react frontend

## Installation

Use the package manager [pip](https://pypi.org/project/pip/) to install [pipenv](https://pipenv.pypa.io/en/latest/) and to initialize the virtualenv for this project use.

```bash
#to install pipenv package
pip install pipenv

#to initialize virtualenv
pipenv shell

#returns 

warnings.warn(
Pipfile.lock not found, creating...
Locking [dev-packages] dependencies...
Locking [packages] dependencies...
Updated Pipfile.lock (e4eef2)!
Installing dependencies from Pipfile.lock (e4eef2)...
🐍   ▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉ 0/0 — 00:00:00

```
## Versions
```python
Python 3.10.1
```
```node
Node 17.3.0
```
## Usage

```python
#to install all packages
pipenv install
```
```node
#to install react packages

npm install or npm i
```


## Run
```python
#checks any migrations
python .\myWebproject\manage.py makemigrations
```
```python
#apply any migrations
python .\myWebproject\manage.py migrate


#returns
Operations to perform:
Apply all migrations: admin, auth, contenttypes, sessions
Running migrations:
Applying contenttypes.0001_initial... OK
Applying auth.0001_initial... OK
Applying admin.0001_initial... OK
Applying admin.0002_logentry_remove_auto_add... OK
Applying admin.0003_logentry_add_action_flag_choices... OK
Applying contenttypes.0002_remove_content_type_name... OK
Applying auth.0002_alter_permission_name_max_length... OK
Applying auth.0003_alter_user_email_max_length... OK
Applying auth.0004_alter_user_username_opts... OK
Applying auth.0005_alter_user_last_login_null... OK
Applying auth.0006_require_contenttypes_0002... OK
Applying auth.0007_alter_validators_add_error_messages... OK
Applying auth.0008_alter_user_username_max_length... OK
Applying auth.0009_alter_user_last_name_max_length... OK
Applying auth.0010_alter_group_name_max_length... OK
Applying auth.0011_update_proxy_permissions... OK
Applying auth.0012_alter_user_first_name_max_length... OK
Applying sessions.0001_initial... OK
```

```python
#run server
python .\mywebproject\manage.py runserver

#returns
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
January 17, 2022 - 10:17:24
Django version 4.0.1, using settings 'myWebproject.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.

```

## React
```react
#to start the server
npm start
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[Apache](https://choosealicense.com/licenses/apache2.0/)
