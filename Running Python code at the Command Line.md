# Running Python code at the Command Line

Often data scientists write their code in a Jupyter notebook and then “refactor it” and refine it into a module that can be used at the command line.

You should have a plain text editor to work with.


This is a good introduction:
[https://opentechschool.github.io/python-beginners/en/getting_started.html](https://opentechschool.github.io/python-beginners/en/getting_started.html)

## Adding Python to Windows path
There are two methods for installing python in windows

- Installing python 3.5 and all its dependencies using Anaconda, which has been already explained in the previous tutorial
- Installing python 3.5 separately

## Running Python at command line in windows

Before running python at the command line in windows we have to make sure that the python is accessible from the command line

- After opening the command line in windows , type python and  press enter

  <img alt="Running Python code at the Command Line-75e2e740.png" src="assets/Running Python code at the Command Line-75e2e740.png" width="" height="" >

If python is installed correctly , you will get a screen like this .

  <img alt="Running Python code at the Command Line-b71f4fed.png" src="assets/Running Python code at the Command Line-b71f4fed.png" width="" height="" >

Else you will get an error message that says

  **“'python' is not recognized as an internal or external command,
  operable program or batch file.”**

This error means that you have not installed python properly or it’s not added to the ENVIRONMENT

Follow the steps to add python to the ENVIRONMENT

- In Search, search for and then Control Panel
-n the control panel click on “SYSTEM AND SECURITY”

<img alt="Running Python code at the Command Line-72d3f8f1.png" src="assets/Running Python code at the Command Line-72d3f8f1.png" width="" height="" >

- Then click on “SYSTEM”

<img alt="Running Python code at the Command Line-ca116156.png" src="assets/Running Python code at the Command Line-ca116156.png" width="" height="" >

- Then select "Advanced System Settings"
    <img alt="Running Python code at the Command Line-0155f77f.png" src="assets/Running Python code at the Command Line-0155f77f.png" width="" height="" >  
- From the popup select “Environment variables”, the following popup will open. Then double click on “path” from the variable
  <img alt="Running Python code at the Command Line-514eba0a.png" src="assets/Running Python code at the Command Line-514eba0a.png" width="" height="" >
- In the following popup which opens click on new
  <img alt="Running Python code at the Command Line-cce7902e.png" src="assets/Running Python code at the Command Line-cce7902e.png" width="" height="" >
- Then you will have to enter the path where your python is installed
  - If you had installed through Anaconda the path will be similar to this
**“C:\Users\username\AppData\Local\Continuum\anaconda3\”**
    - Then click on new again and enter
**“C:\Users\username\AppData\Local\Continuum\anaconda3\Scripts\”**
  - If you had installed python without Anaconda the path will be similar to
**“C:\Users\username\AppData\Local\Programs\Python\Python36-32\”**
    - i.	Then click on new again and enter
**“C:\Users\username\AppData\Local\Programs\Python\Python3632\Scripts\”**

#### Video on how to add Python to ENV in windows 10

[https://www.youtube.com/watch?v=RaECVjRhyF8](https://www.youtube.com/watch?v=RaECVjRhyF8)
