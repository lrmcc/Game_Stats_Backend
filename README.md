# **Game Stats Backend**

### Objective
Accept score data from HTML/CSS/JS games to keep a record of top scores.

### Purpose
This Game Stats Backend will function as a running servicer to collect data and execute score evaluation code in order to create, read, update and delete valid data in a SQL database.

## Setup
This project uses a virtual environment for development. 
This is from the installation instructions at https://flask.palletsprojects.com/en/2.0.x/installation/
To enter the virtual environment from within the code directory (we are using venv, other options exist):
name@name-computer directory %     *source venv/bin/activate*
To exit the virtual environment:
(venv) name@name-computer directory %   *deactivate*

The following environment variables have been set:
(to allow gamestatsbackend.py to be launched with run command)
(venv) name@name-computer directory %   *export FLASK_APP=gamestatsbackend*
to enable development / debugger
(venv) name@name-computer directory %   *export FLASK_ENV=development*  


## Start the program
To start Game Stats Backend execute the following command while in the virtual envirnoment from the terminal:
(venv) name@name-computer directory %   *flask run*

