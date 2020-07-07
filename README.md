# Blog_Python_Flask

This repository includes the code to build a simple functional blog using the Flask microframework from Python.
It is the result of a guided project found online. 

While aesthetics are not the point, the app uses Flask and a bit of bootstrap to create a functional blog that:
-Allows users to create an account, login and logout, including the ability to upload and change a profile image
-Create, read, update and delete posts (CRUD)
-Showcase previous blogs written by other users
-Work with SQLAlchemy and databases to store and retrieve information

Other lessons include:
-Creating a home page and navigation bar
-Creating and understanding the basic structure of the application
-Creating and separating py files and linking them to other files
-Creating views and their respective html templates
-Using jinga templating and the ability to embed python code within an html file
-Getting more comfortable with the command line 
-Debugging: Although this is not a large application, it is certainly large and detailed enough that bugs will occur. 


::::::::::::::::::::Important::::::::::::::::::::
----ONE----
Creating a virtual environment is highly recommended. A Flask application like this one is dependent on various libraries (see the requirements.txt file). 
As these files get updates or possibly deprecated, it will certainly affect your ability to smoothly run your application.

----TWO----
After creating a virtual environment, upload the libraries contained in the 'requirements.txt' file.


----THREE----
The "Migration" Folder is not to be copied. It is there to illustrate what it will look like once you setup your profile and link your database.

After following along and creating your own Flask application, you must go to the terminal and run the following three codes:

flask db init
flask db migrate -m 'first migration' (Insert any title within the quotes as a reference'
flask db upgrade

