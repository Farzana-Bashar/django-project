    $ pip3 install pipenv

    $ pipenv install django
it creates some file/binary file. Also create Pipfile and Pipfile.lock. these are like package.json/package-lock.json file in Nodejs.

### To activate the env
    $ pipenv shell 

### Get all the Commands-
    $ django-admin

Type 'django-admin help <subcommand>' for help on a specific subcommand.

Available subcommands:

[django]
    check
    compilemessages
    createcachetable
    dbshell
    diffsettings
    dumpdata
    flush
    inspectdb
    loaddata
    makemessages
    makemigrations
    migrate
    runserver
    sendtestemail
    shell
    showmigrations
    sqlflush
    sqlmigrate
    sqlsequencereset
    squashmigrations
    startapp
    startproject
    test
    testserver
Note that only Django core commands are listed as settings are not properly configured (error: Requested setting INSTALLED_APPS, but settings are not configured. You must either define the environment variable DJANGO_SETTINGS_MODULE or call settings.configure() before accessing settings.).

### To Start the project
    $ django-admin startproject storefront .

it will create a folder name storefront

### Run the server
    $ python manage.py runserver

### Get the path
    $ pipenv --venv             ///Users/farzana/.local/share/virtualenvs/django-mosh-tN9Ojf_-

### selete python interpreter and paste
    $ /Users/farzana/.local/share/virtualenvs/django-mosh-tN9Ojf_-/bin/python

### activate env
    $ source /Users/farzana/.local/share/virtualenvs/django-mosh-tN9Ojf_-/bin/activate

### add new folder with django structure
    $ python manage.py startapp playground
It will create a new folder name playground 

### Add the new App in setting.py
 add the new add 'playground' in INSTALLED_APPS array.
