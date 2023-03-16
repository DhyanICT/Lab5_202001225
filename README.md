# Lab5_202001225

Name: Dhyan Dineshbhai Patel

Student ID: 202001225

Lab-5

Aim: static Analysis

List of tools:

Python:

  ● Mypy

● Pylint

● Pyflakes

● Pycodestyle (pep8)

● Flake8

● Prospector

● Bandit

From the above tools i have chosen Mypy tool to do static analysis.
first i install "Mypy" tool using cmd command "pip install python".
I downloaded random repo from github which contains python files in order to analyse them and extract some python files to desktop.
Now i simply run the python file using cmd command "python -m mypy file_name.py".


![c1](https://user-images.githubusercontent.com/124245399/225570631-807f2b1e-9bf9-45a8-ab7a-6d6c684cb575.PNG)

In above image we can see that the python file run succesfully without any type of error.

Now let's run another file from the downloaded repo.

![image](https://user-images.githubusercontent.com/124245399/225573829-5fc5faa1-0188-421d-a53a-7a4a502049b0.png)

In the above image we can see that one error pop-up when we try to run the given file. The error is indicating that on the 20th line of code we have syntax error.
from this mypy tool we can easily recognize the error in python file and handle it accordingly.

![image](https://user-images.githubusercontent.com/124245399/225575716-1c43fcf3-c9fa-4941-ac34-28e457d2223c.png)

In the above image we can see that error arise that "tk" not defined that indicates that in the source code there should be "tk" variable which is used without
defining it and it is used 27 time in source code.

![image](https://user-images.githubusercontent.com/124245399/225577869-af82ec2b-010b-4a00-8ecd-0a13fbac9ec7.png)

In the above image we can see two errors indicating that cannot find libraries "helper.string" and "helper.math".
