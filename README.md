# full_throttle


#READme

Bulding an application to jet the login times of a user.

Step 1:

-> Creating a pycharm project
-> Starting a Django project

$ django-admin startproject full_throttle

-> starting an app now

$ python manage.py startapp full_throttle

-> Adding the new app to settings.py

-> Testing all are good my running the server

$ python manage.py runserver

-> if everything is good, we will be able to see django message in localhost at "127.0.0.1:8000"

-> Now our primary goal is to store user details and session times correspondingly

-> here we are creating 2 models User, ActivityPeriod

-> adding them to admin.py

-> writing a view fuction to post the data as json to site

-> updating in urls.py

-> creating a superuser to maintain the database

$ python manage.py createsuperuser

Note:

	Data in the page is added through database,
	
	Taking user id as ForeignKey to ActivityPeriod Model.
	
	Please go through the code.
	
	everything is ready for deployement.
	
	I have tested on Azure.
	
	And I also added the screenshots of the results.
	
	
	
#####THANKYOU#####
