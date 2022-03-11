INTRODUCTION
------------
In this project you can upload a image of a car and predict its make, year and model.

REQUIREMENTS
------------
Python 3.9 installed

HOW TO RUN
------------

There are two folders
ml-api 
myapi 

ml-api contains the environment
myapi contains the project

So in order to run the project you need to go to activate the environment 
from command line you can use 
ml-api\Scripts\activate.bat

it will open a environment
and then go to myapi folder and run 
python manage.py runserver

Open browser and navigate to http://127.0.0.1:8000/
The page contains a upload and predict button.

Once the image is uploaded the predict button will be enabled. And when you click on the predict it will predict the make, model and year and show the confidence level of the prediction inside the bounding box.
"# testingGid" 
