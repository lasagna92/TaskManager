# Task Manager
## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
***
### General Info
***
This is an application to insert, modify, organize and overview tasks.


The user after log in (the usernames and passwords are stored in a text file) can do the following:
* View all the tasks
* View the logged-in user's task
* Add a new task
* Edit a task 

The admin after log in can do the following:
* Register a new user
* Add a new task
* View all the tasks
* View the logged-in user's task
* View statistics
* Generate reports

USER REGISTATION: 
* Insert a username, password and password confirmation. If the username isn't is use, add the details to the user.txt file 

ADD A TASK (Append the details to the tasks.txt file):
* Username for the task 
* Name of the task 
* Description of the task
* Due date 

EDIT A TASK (Modify the tasks.txt file):
* Modify the due date and/or the username
* Mark the task as complete

VIEW ALL THE TASKS:
* Disply all the tasks in a tidy manner

VIEW MINE:
* Display the user's tasks in a tidy manner

GENARATE REPORTS:

Generates the task_overview.txt which displays:
* Total number of generated tasks
* The total number of completed tasks
* The total number of uncompleted tasks
* The tasks that are overdue
* The percentage of uncompleted tasks
* The percentage of overdue tasks

And the user_overview.txt which displays:
* The total number of registered users
* The total number of tasks generated 
for each user displays:
* The total number of tasks assigned to that user
* The percentage of assigned tasks
* The percentage of completed tasks
* The percentage of uncompleted tasks
* The percentage of overdue tasks


### Technologies
***
The technology used for this project is [Python 3.10.9](https://www.python.org/downloads/release/python-3109/) 

### Installation
***
A little intro about the installation. 
```
$ git clone https://github.com/lasagna92/TaskManager.git
$ cd ../path/to/the/file
$ npm install
$ npm start
```
