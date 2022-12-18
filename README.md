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
![image](https://user-images.githubusercontent.com/72568844/208298110-f6cdd157-ea3d-4493-a468-3a487af30afe.png)

3) Click `Create fork`.  
**Warning: Don't change anything!**  
![image](https://user-images.githubusercontent.com/72568844/208298135-699d1bb0-cb00-4ac9-9dfd-03514ab70bb9.png)

4) Complete! Repo The repository must be forked.  
![image](https://user-images.githubusercontent.com/72568844/208298180-8873f14c-8397-4785-8282-9a5e055e26f9.png)


### How to clone repository

1) Copy SSH key from repo  
![image](https://user-images.githubusercontent.com/72568844/208298243-dfcc7264-3c65-46ed-b1d2-4815b10c0f7d.png)

2) Open project folder on terminal (ex: Windows)  
![image](https://user-images.githubusercontent.com/72568844/208298402-29998fda-2b72-43af-aff2-b4e34caa9399.png)  
![image](https://user-images.githubusercontent.com/72568844/208298330-48d5e2c8-5d06-4de7-a1c8-29fdc50e4896.png)

3) Run command
`git clone {paste copied SSH}`

4) Enter your password (if it's need)  
![image](https://user-images.githubusercontent.com/72568844/208298358-df7e16cb-af21-4995-bdd6-92bcbb0e4980.png)

5) Complete!  
![image](https://user-images.githubusercontent.com/72568844/208298372-24ff7fcd-0169-4f8a-9dc2-2360f65aee24.png)  
![image](https://user-images.githubusercontent.com/72568844/208298387-5b8d48c2-56fc-462d-8ed2-f448ac24a16b.png)



### How to set up your project

1) Open downloaded folder with IDE (PyCharm, VS Code or other):  
Example 1:  
![image](https://user-images.githubusercontent.com/72568844/208298454-9f9f644f-23c1-4681-8c09-cf26c3759a68.png)
Example 2:  
![image](https://user-images.githubusercontent.com/72568844/208298480-fd3a5b5f-f198-4ba2-9264-2e02b3e477e3.png)  
![image](https://user-images.githubusercontent.com/72568844/208298525-2b95fe32-d8d3-4f0e-ae94-82928d563f40.png)

2) Open terminal in IDE:  
![image](https://user-images.githubusercontent.com/72568844/208298549-8281dcf2-f1d2-47a5-84e1-7c2ede69bbaa.png)

3) Create virtual environment:  
Run command: `python -m venv venv`  
_**(Python 3.10 recommended)**_

4) Activate virtual environment:  
![image](https://user-images.githubusercontent.com/72568844/208301307-acc9c37e-0692-4649-9661-142799cadcd6.png)  
![image](https://user-images.githubusercontent.com/72568844/208301342-ec53c20c-4ec7-46a4-9f0b-8289a73df0f2.png)  
Restart your terminal:  
![image](https://user-images.githubusercontent.com/72568844/208301678-a87d52c8-5f12-47fd-8da5-115faad0b6a2.png)

5) Install requirements:  
Run command: `pip install -r requirements.txt`

6) Create new branch:  
Run command: `git checkout -b develop`  
You can replace `develop` with `{username}_develop`  
![image](https://user-images.githubusercontent.com/72568844/208298592-9d9db1a2-ecf8-4f86-9d39-3bb4f022d2a2.png)

7) Let's start your work!


### How to run tests
Run command: `pytest` in terminal


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
#### If you push your solution right now:
1) Click on `link` in terminal:  
![image](https://user-images.githubusercontent.com/72568844/208298701-7f68933b-ef08-4f46-8283-46a536da425a.png)

2) Click on `Create pull request`  
![image](https://user-images.githubusercontent.com/72568844/208298720-621dac08-3d15-48f4-a832-5f53f74f4200.png)
  

#### If you lose this link, just go to GitHub repo and do some actions:
1) Open `branches` on your repo:  
![image](https://user-images.githubusercontent.com/72568844/208298795-7b2d8fbd-730c-49c8-8b74-447a9b351a17.png)

2) Click to `New pull request` on your branch:  
![image](https://user-images.githubusercontent.com/72568844/208298846-9f2eebd6-84dc-4367-8e61-c64739fc27fc.png)

3) And now just click on `Create pull request`  
![image](https://user-images.githubusercontent.com/72568844/208298865-9c6c8548-345a-4220-913f-05e72ea5ad61.png)
