# Application

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/manvirchanna/libraray-management.git
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```

Once `pip` has finished downloading the dependencies `cd` into the directory where `manage.py` is:

```sh
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000`.

The project will start working 

credentials for 

admin:
url: `http://127.0.0.1:8000/admin`
username: manvir
password: manvir


librarian:
url: `http://127.0.0.1:8000/adminlogin`
username: admin
password: admin

student:
url: `http://127.0.0.1:8000/studentlogin`
username: student
password: student


If any query or question ask me at manvirchanna247@gmail.com