
# Curling Simulator onboarding website
## This website will serve as onbaoarding for future students or anyone curious about our research.
## In our research we are using a physics simulator and python. There will be interactive models throughout the page for both the physics and python.

## Features
- interactive models
- in depth documentation of both python and physics 
- page to download all software needed 
- Team page

# Tech
This website along with the curing simulator uses a few open source project to work
- <ins>Python 3</ins> - All the coding you will do and see will be in python
- <ins>Pip</ins> - This is so you are able to install the virtual environment (this is typically installed when python is installed)
- <ins>Pipenv</ins> -This is for virtual environments to install our application depencdies without interuppting others projects 
- <ins>Visual studio code(Vs code)</ins> - This is an app to do all the coding once you feel comfortable
- <ins>Django</ins> - This is a python backend for our websites
- <ins>MuJoCo</ins> - Physics engine used for simulator
- <ins>MuJoCoPy</ins> - Python frontend to support the simulator
- <ins>Github</ins> - Allows for easy collaboration (optional)

## Installation
For django to run you will need to install python
This will all be done in either termanial or command prompt

You can install [Python 3](https://www.python.org/downloads/)

To make sure the download was successful type:

|OS| Command |
|---|---|
|Mac|python3 --verison|
|Windows| python --verison|

If pip is not installed you can run:

|OS| Command |
|---|---|
|Mac|python3 -m ensurepip --upgrade|
|Windows|py -m ensurepip --upgrade|

or 

|OS| Command |
|---|---|
|Mac|python3 get-pip.py|
|Windows|py get-pip.py|


Now install pipenv type:

|OS| Command |
|---|---|
|Mac|pip3 install pipenv|
|Windows|pip install pipenv|


Making an directory (folder) type:

|Os|command|
|---|---|
|all|mkdir directoryName|

Then type to enter the directory (folder) you just created:

|Os|Command|
|---|---|
|all|cd directoryName|

Now to use django you will need to create a virtual environment and download django within that environment type:

|OS| Command |
|---|---|
|Mac|pip3 install pipenv|
|Windows|pip install pipenv|

Open [Visual Studio Code](https://code.visualstudio.com/download) commonly refered as VS code and open your folder that you just created

Install python extension

## Creating django project

Make sure you are inside your directory
We are now going to create a virtual environment for our project along with installing django within that virtual environmnet

|OS|Command|
|---|---|
|all| pipenv install django|

Now open VS code and open your project folder as well.

You will now also see two file one called "Pipfile" and another called "Pipfile.loc"

Now back in the terminal we will need to active the virtual environment 

|OS|Command|
|---|---|
|all|pipenv shell|

Starting a new project

|OS|Command|
|---|---|
|all|django-admin startproject projectName .|

### Notes
* You will need to active the virtual environment everytime you work on the project
* Do not include your vitural environment into Github (.gitignore)



The dot at the indicates that we want it in the directory we are currently in





