# DEvops
Besant_Devops 


Devops


CI/CD pipeline - continuous intergration and continuous deployment

Git&Github
Docker
Terraform
Kubernetes
Jenkins
Ansible
Nagios


Git - we are writing the code ffor a new application to store the same code, we are usingthe git

2 - we already written the code for the application again we write the new code for updated version, 
all these version are we stored in the git - we called it as VCS - version control system / source code managament 


Git stages =

Working directory  - Git add-> staging area
Aftr git installation in EC2 instaces the local files are avaiable in git and u can edit the code modify and delete


Staging area    - Git commit -> repository
files transfer from working directry to staging area by using the commands git add 


Repository 
from SA to repository we are going to send the files by using git commit 
whatever the changes we made in coding u can reflect the code by using the git commit in the repository

				central repository					===== Final code

			|		|			|
		dev1		dev2		dev3		all thse task are together called local repository
			|		|			|
		task1		task2		task3

when we push the changes to central all task gets merged andmove to final code 


Types of repository		
		
Local repository - In Local repository we have to integrate single code from all the developers code from cetral repo
		
Central - Will contain all the developers code 


Remote- dev 1,2,3,4 - here from dev1 code need to share without knowing dev2,dev3 to dev 4
in this case we will create remote repository then it will send code to dev4

yum install - y
ll - to see file
ls -al

	
git init

git init .
git status 
touch f1
cat > f1  = control + c 

git add f1
git commit -m "file1"
git log


user configuration


git config user.name "jithu"



 yum install git -y
    2  git version
    3  git --version
    4  ll
    5  ls -al
    6  git init .
    7  ll
    8  touch f1
    9  ll
   10  cat > f1
   11  git status
   12  pwd
   13  git add f1
   14  git status
   15  git commit -m
   16  git commit -m "file1"
   17  git log
   18  clear
   19  git config user.name "jithu"
   20  git config user.email "jithu123@gmail.com"
   21  touch f2
   22  cat > f2
   23  git add f2
   24  git status
   25  git commit -m "file2"
   26  git log
   27  ls
   28  cd root
   29  pwd
   30  ls
   31  cd f1
   32  ls
   33  git log
   34  history

_______________________________________________________________________________________________________________

Day 2

_______________________________________________________________________________________________________________






