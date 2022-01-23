# Project

This is a personal project based on django framework and react frontend

## Installation

Use the package manager [pip](https://pypi.org/project/pip/) all the packages for this project use.

You can use [pipenv](https://pypi.org/project/pipenv/) or [Virtualenv](https://pypi.org/project/virtualenv/) or [Conda](https://www.anaconda.com/products/individual)
```bash


#to install pipenv package
pip install pipenv
```
```bash
#to install venv package
pip install venv

Create the virtual environment
To create a virtual environment, you must specify a path. For example to create one in the local directory called ‘mypython’, type the following:

virtualenv mypython
ot venv mypython

Activate the virtual environment
You can activate the python environment by running the following command:

Mac OS / Linux
source mypython/bin/activate

Windows
mypthon\Scripts\activate




Deactivate the virtual environment
To decativate the virtual environment and use your original Python environment, simply type ‘deactivate’.

deactivate
```


```bash

#to initialize pipenv's virtualenv
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
Python 3.9.7
```
```node
Node 16.13.2(LTS)
```
## Usage

```python
#to install all packages

#for pipenv
pipenv install


#for others
pip install -r requirements.txt 
```
```node
#to install react packages

npm install or npm i
```


## Run
```python
#checks any migrations
python manage.py makemigrations
```
```python
#apply any migrations
python manage.py migrate


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
 python manage.py runserver

#returns
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
January 20, 2022 - 19:15:41
Django version 3.2.5, using settings 'Project.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.


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
[Apache](http://www.apache.org/licenses/LICENSE-2.0)
