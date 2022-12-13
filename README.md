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
![image](https://user-images.githubusercontent.com/72568844/207454345-9305f8ab-484b-4b74-9ab4-ae4948a1a6d0.png)

3) Click `Create fork`.  
**Warning: Don't change anything!**  
![image](https://user-images.githubusercontent.com/72568844/207454436-ff02e137-546e-468b-83ba-f25761d9f7ff.png)

4) Complete! Repo The repository must be forked.
![image](https://user-images.githubusercontent.com/72568844/207454503-d18e16d0-10e3-4369-a4b4-31dfbc725d26.png)


### How to clone repository

1) Copy SSH key from repo  
![image](https://user-images.githubusercontent.com/72568844/207454593-1c7bbe71-f19a-48a1-bc63-6e9519886836.png)

2) Open project folder on terminal (ex: Windows)  
![image](https://user-images.githubusercontent.com/72568844/207454628-6d14e5be-e5f0-4dd9-a943-44ddf29777d2.png)   
![image](https://user-images.githubusercontent.com/72568844/207454747-7dcd2890-3bf5-4f79-988c-4364617328c2.png)
3) Run command
`git clone {paste copied SSH}`
4) Enter your password (if it's need)
5) Complete!  
![image](https://user-images.githubusercontent.com/72568844/207454819-f5348e93-8647-4b18-81b0-157598a26383.png)


### How to set up your project

1) Open downloaded folder with IDE (PyCharm, VS Code or other):  
Example 1:  
![image](https://user-images.githubusercontent.com/72568844/207454855-6fcae3f4-909e-4d8c-a5c1-18fc6f6df4e4.png)  
Example 2:  
![image](https://user-images.githubusercontent.com/72568844/207454888-3fcddcf8-8c8e-437a-9564-9f7439b9b9a8.png)
![image](https://user-images.githubusercontent.com/72568844/207454907-fe8a15c4-1653-47e5-9d3d-fbd1ab61e566.png)
2) Open terminal in IDE:  
![image](https://user-images.githubusercontent.com/72568844/207454989-a88c4213-55aa-40d2-b4c5-07ecc8456374.png)
3) Create virtual environment  
Run command: `python -m venv venv`  
_**(Python 3.10 recommended)**_
4) Install requirements:  
Run command: `pip install -r requirements.txt`
5) Create new branch:  
Run command: `git checkout -b develop`  
You can replace `develop` with `{username}_develop`  
![image](https://user-images.githubusercontent.com/72568844/207455056-6dc3e5f8-9c27-4fb2-96a9-fff084920f12.png)
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
![image](https://user-images.githubusercontent.com/72568844/207455119-35c032e6-0d7b-4e12-992e-ca75ffd21550.png)
2) Click on `Create pull request`
![image](https://user-images.githubusercontent.com/72568844/207455199-b8fe7d7e-ec31-4e26-a61e-237272992e3d.png)
  

If you lose this link, just go to GitHub repo and do some actions:
1) Open `branches` on your repo:  
![image](https://user-images.githubusercontent.com/72568844/207455544-938f458e-ac0a-4723-a34d-4d7642c3a24c.png)
2) Click to `New pull request` on your branch:  
![image](https://user-images.githubusercontent.com/72568844/207455692-02c7b282-5d8b-4377-9e0e-7e2101754112.png) 

3) And now just click on `Create pull request`  
![image](https://user-images.githubusercontent.com/72568844/207455724-a51f4980-6d4e-4899-a8b6-6e8eb1734610.png)
