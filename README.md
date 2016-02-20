# Django-Polls-App

Basic poll application based on the django tutorial consisting of two parts:
* A public site that lets people view polls and vote in them.
* An admin site that lets you add, change, and delete polls.


And its current `requirements.txt` file is:

```
Django==1.9.2
wheel==0.24.0
```

## Installation

### 1. virtualenv / virtualenvwrapper
Create [virtualenv](http://www.virtualenv.org/) for your own project, where `projectname` is the name of your project:

Install virtualenv via pip:

`$ pip install virtualenv`

1. Create a virtual environment for a project:
  ```
 $ virtualenv projectname
```
 
2. To begin using the virtual environment, it needs to be activated:
   ```
  $ cd projectname
  $ source bin/activate
```


### 2. Download
Now, you need the *django-polls-app* project files in your workspace:

    $ cd /path/to/your/workspace
    $ git clone git://github.com/kishan/Django-Polls-App.git polls_app
    $ cd polls_app

### 3. Requirements
Right there, you will find the *requirements.txt* file that has all the great debugging tools, django helpers and some other cool stuff. To install them, simply type:

`$ pip install -r requirements.txt`

### 4. Tweaks

#### Initialize the database

`python manage.py migrate`

### 5. Runserver

`python manage.py runserver`
