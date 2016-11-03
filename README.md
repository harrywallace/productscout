# productscout
This is a skeleton Django app, that should be used for the MyFinance code challenge

## Requirements
* python v2.7
* virtualenv (recommended)
* virtualenvwrapper (also recommended)

You can find a great guide for how to install, configure, and use all of these [here](http://docs.python-guide.org/en/latest/starting/installation/)

## Setup
Before following these next steps, make sure you have cloned down this repository to your local machine, and that you have navigated to the root directory of the repository. Also, it is recommended that you create and activate a virtual env for the project.

Once all the above has been completed, next install ```pip``` dependencies using ```./requirements.txt```:

```
$ pip install -r requirements.txt
```

Verify ```pip``` dependencies installed correctly under ```virtualenv```:

```
$ which django-admin.py
```

Apply initial migrations:

```
$ python productscout/manage.py migrate
```

Start the django dev server:

```
$ python productscout/manage.py runserver
```

Then, navigate to the displayed address in your browser, and make sure that the index page is loading properly. You're ready to start!
