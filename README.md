## Graded Assignment on Git and GitHub ######################################################################################################################

(A) First of all create repo on Git hub by the Name the of git_assignment_HeroVired .

Repo is Private and READ MD & .gitignore file also add .

Used this command on gitbash in Local :- git clone sshURL .

Dir will create on local by the name of git_assignment_HeroVired go to in it.

(B) For Creation dev branch used this command on git bash :- 
1=>git branch dev

2=>git checkout dev
Now we are in dev branch 
code . Used this command on git bash for go to in Vs code  

3=>The Code which given in assignment by the name of CalculatorPlus with .py extiontion need to save it on VS code .
This application provides basic arithmetic operations, such as addition, subtraction, multiplication, and division. 

4=>Used the command git add  CalculatorPlus.py for Tracked file or (git add . for all files which are not tracked)

5=>Use this command for save msg and commit :- 

git commit -m "Fix:- The application provides basic arithmetic operations, like  addition, subtraction, multiplication, and division"

6=>Push the changes to remote repository on dev branch :- 

git push -u origin dev

7=> Now Add the new code for function to calculate the square root of a number so that we can implementation to add the square root feature.

To tracket file 

git add .  

git commit -m "New Function add the square root feature"

Now Push code to dev branch 

git push -u origin dev

8=> square root feature Fixed 

Tracked file
git add .

save changes and commit
git commit -m "FIXED:- square root feature"

Push the changes to remote repository on dev branch :- 
git push -u origin dev

(C) Merge this branch with the main branch Used below command on git bash :- 

git checkout main

git pull

git checkout main

git tag version1

git push origin version1

Go to github UI take refresh

Tag option will show version name 

go to release option on right side of git Hub select tag name describe comments in comments option select target main and save.

(D) Go to setting of repo 

Click on collaborators options and click on add people under manage access provide user name and click button .
 under manage access user name invite option wiil be pending .
 under notification option user which received collaborators request accept invitation  

 (E) Create branch by the name of feature/sqrt.f by below command 

  git branch feature/sqrt.f

   git checkout feature/sqrt.f

   (F) Add the ‘sqrt’ code to CalculatorPlus.py 

   Tracked file
   git add .

   git commit -m " Add feture/sqrt.f branch"

   Now Push code to feture/sqrt.f branch on remote repo

   git push -u origin feature/sqrt.f

   Take refresh from Git UI new branch wiil add with code .

   
 

