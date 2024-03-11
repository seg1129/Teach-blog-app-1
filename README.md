# Teach-blog-app-1
This repo will be used to teach students how to create their first web application. We will be building a blog app using Django web framework

# Initial Local Environment setup
We will be using a python web framework called Django for this excersice of building a simple blog web application. To get your local environment set up you will need to have 
- Python 3.10, 3.11 or 3.12,
- a python virtual Enviroment and
- Django version 5.0.

If you already have python and a python virtual environment set up, go ahead and skip to 'Downloading Django' to prepare for this session. 

## Installing Python
There are many different ways to install python, here I will give two resources that I find helpful. 
### Install a single version of Python
If you think you will not use multiple versions of python then you can go directly to [python.org](https://www.python.org/downloads) and download version 3.10, 3.11 or 3.12.
### Managing multiple versions of Python
I use pyenv to manage multiple different versions of python on my machine, it also works well with common python virtual enviroment tools. Follow [these steps](https://realpython.com/intro-to-pyenv/) to get pyenv set up on your machine. 

## Using a Python Virtual Enviroment
Using a python virtual enviroment allows you to have multple project on your machine at once without having different versions of python or libraries conflict with eachother. I highly recommend using virtual enviorment to manage all of your python projects. You can read [here](https://realpython.com/python-virtual-environments-a-primer/#why-do-you-need-virtual-environments?) for more information about this. Here are some resources, you only need to select one of these tools to use:
- [pyenv virtual enviroment set up](https://realpython.com/intro-to-pyenv/#virtual-environments-and-pyenv)
- [Python's venv](https://realpython.com/python-virtual-environments-a-primer/)
- [virtualenv](https://realpython.com/python-virtual-environments-a-primer/#the-virtualenv-project) This tool is a superset of python's venv.

  Note: I do not reccomend using conda due to all of the additional libraries it downloads.

## Downloading and setting up Django
1. Create a new python virtual enviornment using python version 3.10, 3.11 or 3.12 and give the env a unique name.
2. Install Django
   - Linux/ MacOS: `python -m pip install Django==5.0.3`
   - Windows: `py -m pip install Django==5.0.3`
3. Verify your installation worked: `python -m django --version` output should be the version of Django you installed.
4. Navigate to the file system that you want to store you code for this project.
5. Create a Django project - This will auto-generate some code for your new project. `django-admin startproject firstWebApp`
6. Create a Django app - This will also auto-generate some code for your new application. Before running, make sure you are in the same directory, in your project, as file 'manage.py'. `python manage.py startapp blog`
7. Run the development server `python manage.py runserver 8000`
8. Navigate to the web browser `localhost:8000` and you should see a blue Django ribbon with a log in page. This is an indication that your project is all set up and you are ready to go!

