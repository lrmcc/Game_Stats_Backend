# **Game Stats Backend**

## Objective  
Accept score data from HTML/CSS/JS games to keep a record of top scores.

## Purpose   
This Game Stats Backend will function as a running servicer to collect data and execute score evaluation code in order to create, read, update and delete valid data in a SQL database.  

## Setup 
This project uses a virtual environment for development.  

Detailed installation instructions can be found at https://flask.palletsprojects.com/en/2.0.x/installation/  

### Enter the virtual environment
To enter the virtual environment from within the code directory (we are using venv, other options exist):  
name@name-computer directory %     *. venv/bin/activate*  

Within the virtual environment, install flask (may need to use pip3):  
name@name-computer directory %     pip install Flask

The FLASK_APP and FLASK_ENV environment variables have been set as shown below for this project's development environment.  

To allow gamestatsbackend.py to be launched with run command:  
(venv) name@name-computer directory %   *export FLASK_APP=gamestatsbackend*  

To enable development / debugger:  
(venv) name@name-computer directory %   *export FLASK_ENV=development*  

## Start the program
To run the Game Stats Backend execute the following command while in the virtual envirnoment from the terminal:  
(venv) name@name-computer directory %   *flask run*  

Flask should start the server which can be found in a browser running at the default http://127.0.0.1:5000/ 

## Close the program
From the terminal where Game Stats Backend was launched in the virtual environment
as noted from the Flask generated messages, Press CTRL+C to quit

### Exit virtual environment
To exit the virtual environment:  
(venv) name@name-computer directory %   *deactivate*  
  


