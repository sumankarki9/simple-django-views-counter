# Simple Django App/Simple Django Views Counter App
This is a simple, minimal Django app intended to help understand the main aspects of working with Django.

## Usage Instructions
Clone this repository e.g.

```bash
$ git clone https://github.com/sumankarki9/simple-django-views-counter.git
```

after you cloned repo, go to the cloned repo directory and run the following command

```bash

cd simple-django-views-counter/cool_counters #Moving into the project folder

$ virtualenv -p python3 env # Creating virtual environment

$ source env/bin/activate # To activate virtual-environment ; Type deactivate to deactivate the virtual environment

$ pip install Django # Install Django

$ python manage.py makemigrations
```
This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash  
$ python manage.py migrate
```
One last step and then our App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash

$ python manage.py createsuperuser
```
That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash

$ python manage.py runserver
```
Once the server is hosted, head over to http://127.0.0.1:8000 for the App.
