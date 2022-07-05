# Mail manager
A Django project allowing to manage mails in different categories.

## Install project
```bash
$ git clone git@github.com:PhenYonathan/mail_manager.git
```

## Setup database
```bash
$ python manage.py migrate
```

### Requirement
To use the project a virtual environment is required.

### Versions
> Python 3.9
> 
> Use the requirements.txt file for install requirements

# How to use
## Log in
To be able to access the content, you must create an account with the following command.
```bash
$ python manage.py createsuperuser
```

## Configure the project
In mail_manager folder use exemple_env file and rename to ".env". (All information is provided above.)

## Add search words
### Step 1
Go to the administration interface.

### Step 2
In "App_Manager" go to "Liste statuss"

### Step 3
Click on add and choose between "ras" and "error" for status field, and enter the word in word field.