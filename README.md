# Tasks Guideline
A guide to cloning tasks and how to complete them.

## Upload task
You will have to clone git repositories to complete the tasks.  
So, steps for doing it:
1) Fork
2) Clone
3) Set up project
4) Complete your task and run tests
5) Push solution
6) Create pull request


### How to fork the repo

1) Open repo on `GitHub`.

2) Click `Fork` in the top right corner.  
--- Attach Screenshot 1 ---

3) Click `Create fork`.  
**Warning: Don't change anything!**  
--- Attach Screenshot 2 ---

4) Complete! Repo The repository must be forked.
--- Attach Screenshot 3 ---


### How to clone repository

1) Copy SSH key from repo  
--- Attach Screenshot 4 ---

2) Open project folder on terminal (ex: Windows)  
--- Attach Screenshot 5 ---  
--- Attach Screenshot 6 ---
3) Run command
`git clone {paste copied SSH}`
4) Enter your password (if it's need)
5) Complete!  
--- Attach Screenshot 7 ---


### How to set up your project

1) Open downloaded folder with IDE (PyCharm, VS Code or other):  
Example 1:  
--- Attach Screenshot 8 ---  
Example 2:  
--- Attach Screenshot 9 ---  
--- Attach Screenshot 10 ---
2) Open terminal:  
--- Attach Screenshot 11 ---
3) Create virtual environment  
Run command: `python -m venv venv`  
_**(Python 3.10 recommended)**_
4) Install requirements:  
Run command: `pip install -r requirements.txt`
5) Create new branch:  
Run command: `git checkout -b develop`  
You can replace `develop` with `{username}_develop`  
--- Attach Screenshot 12 ---
6) Let's start your work!


### How to run tests
--- it should be implemented ---


### How to push your solution on GitHub
1) Open terminal
2) Commit your solution:  
Run command: `git commit -am "Solution!"`  
_You can replace "Solution!" with other commit name_
3) Push your solution:  
Run command: `git push origin develop`  
_**You should replace "develop" with your branch name!  
(if you were change it)**_


### How to create pull request
If you push your solution right now:
1) Click on `link` in terminal:  
--- Attach Screenshot 13 ---
2) Click on `Create pull request`


If you lose this link, just go to GitHub repo and do some actions:
1) Open `branches` on your repo:  
--- Attach Screenshot 15 ---  
2) Click to `New pull request` on your branch:  
--- Attach Screenshot 16 ---  

3) And now just click on `Create pull request`  
--- Attach Screenshot 17 ---  