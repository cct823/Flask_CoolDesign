# Flask_learning_progress

## Install the Environment
Tutorial: https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

**Below commands only available for python version not older than 3.4**


To Install the Virtual Environment:

`python3 -m venv venv`

To activate the Virtual Environment(On Mac/Linux):

`source venv/bin/activate`

To activate the Virtual Environment(On Windows):

`venv\Scripts\activate`

Following command allows you to run `Flash Run` automatically when you start virtual environment

`pip install python-dotenv`


## To add a new page 

1. Create a new html file, which inherit from base.html 
2. Modify base.html, add another href in <div></div> section.
3. Modify route.py, add another function, also make sure you add @app.route to allow 
program which file are you linked to.


