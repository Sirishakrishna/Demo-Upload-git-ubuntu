# demo-upload-git-ubuntu
Uploading Demo Project to Github Repository in Ubuntu
Storing our project in github

-Pre-requisite

1. git should be installed in your machine and global configuration should be done after installation.

2. github account for uploading project in a centralized repository.

-Downloading

https://git-scm.com/downloads

-Verify

To check whether git is installed properly or not use command prompt and type "git". If you can see all the available commands in it then installation is done properly.

### Global Configuration

-> $git config --global user.name "<username>"

Example: git config --global user.name "Sirishakrishna"

-> $git config --global user.email <email-id>

Example: git config --global user.email sirisha.velampalli@gmail.com

### Create demo project

For uploading into github repository we created sample demo project in IntelliJ IDE. 
Navigate to the location where your project is located.

Example: sirisha@sirisha-Inspiron-3558:~/IdeaProjects/Demo$

Run the following commands:

(i) $git init: Creates a empty repository

(ii) $git add .: . represents to make all the files available for next commit

Example: sirisha@sirisha-Inspiron-3558:~/IdeaProjects/Demo$ git add .

(iii) Commit: $git commit -m "Message to be displayed"

sirisha@sirisha-Inspiron-3558:~/IdeaProjects/Demo$ git commit -m "Demo"

### Login to github 

git remote add origin https://github.com/Sirishakrishna/demo-upload-git-ubuntu.git //links git repository with local machine project

sirisha@sirisha-Inspiron-3558:~/IdeaProjects/Demo$ git push -u origin master
Username for 'https://github.com': Sirishakrishna
Password for 'https://Sirishakrishna@github.com': 


