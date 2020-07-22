# webdesignfdp3
This repository created for webdesign using reactjs fdp3


#  Web Design Using React Js


# Day Wise -01 

[Recording video1](https://drive.google.com/file/d/1IBYXYrlL1QKIwrKupau_yzcE21hppRRH/view?usp=sharing)

[Recording video2](https://drive.google.com/file/d/1xH7E7IWtss6nrPshQ6ERX0a-YC4yU9vk/view?usp=sharing)

### Day 01


#### What is Web Design ?
             Creating  a website(Static or Dynamic) based on requirement is known as Web Design.

#### What is Web Development ?
               Maintaining the website is known as Web Development(able to perform all DataBase operations).

#### Software Requirements for our project :
                                            1. Text Editor (Sublime Text, Visual studio)
                                            2. Git and Github
                                            3. Chrome
                                            4. Nodejs software


#### Importance of Git and Github in our project:
                    Github is an distributed version control system which maintains the versions of our project.

  ##### Advantages of Github :
                              1. We are able to deploy our project, whenever we want able to get back to previous code by using snapshots
                              2. We can also contribute with other's project 
                              3. open source and also works as social network

 **To create a Github Account** [Official url for Github](https://github.com/)

 #### What is Git ?

                  Git is a tool which manages the snapshots of or project and able to handle small or very large projects effictvely

 **Github uses tool Git to manage the snapshots of the project**


 ##### Installation of Git tool [official website for Git tool](https://git-scm.com/)


 ##### Create a Empty Repository in Github :
                                            1. To create a repository at top-right there is a "+"  dropdown button select that button
                                            2. Select "New Repository" option
                                            3. Name your repository (Repository name should be unique)
                                            4. Make your repository as public (Anyone on the internet are able to see your repository)
                                            5. Initialize your repository with readme file (readme file is completely used for documentation)
                                            6. select option "create repository"

**Readme.md file importance**: 

                            Readme.md file is used for documentation in Github repository by using Markdown syntax


#### Documentation in Markdown format [official url for Mastering Markdown](https://guides.github.com/features/mastering-markdown/)


## Commands in gitBash :

**git config --global user.name "username"** :  This command is used to configure our username into git tool

**git config --global user.mail "mailid"**   :  This command is used to configure our mailid into git tool

**pwd** : This command is used to check the path (pwd stands for present working directory)

**cd Desktop** : This command is used to change our directory to DESKTOP.

**git init** : This command will initialize a git repository 


##### Cloning a Repository from Github Account to local system :


                                                                 1. We have to clone(copy) our repository to local system where we are going to perform our necessary operations to our project
                                                                 2. Cloning a repository will create a folder in localsystem with same name of repository.


  #### How to clone a Repository : 

                                    1. open the repository and then select clone option
                                    2. Copy the url
                                    3. open the gitbash
                                    4. check the path again if you are not in DESKTOP change your path to DESKTOP.



 ### Commands to clone a repository using gitBash


 **git clone paste the url** : This commands clone a repository from github and creates a folder in our local system.

 **ls** : This command is used to display the list of files.

**cd foldername** : This command is used to enter into cloned repository

**mkdir css** : This command is used to create a folder

**mkdir image** : This command is used to create a image folder

**mkdir js** : This command is used to create a js folder.

**touch index.html** : This command is used to create a index.html file.


### Commands to push the changes from local folder to Github repository 


**git status** : This command is used to check the status of the git (If the file is in red color i.e. untracked file,if the file is in green color i.e. tracked file)

**git add .** : This command is used to add all the files from untracking area to tracking area.

**git commit -am "commitmessage** : This command is used to save all the changes with a commit message

**git remote** : This command is used to check the remote (by default we have "origin" remote)

**git push origin master** : This command is used to push the changes to github repository.

**Important note if we want to push the changes again(?second time) we have to fetch and pull**


**git fetch origin** : This command is used to fetch the changes to remote.(Here the default remote name is origin)

**git pull origin master** : This command is used to pull the repository in Github.

**git push origin master** : This command is used to push the chnages from localfolder to Github Repository.


## Day 02:

[Recording video1](https://drive.google.com/file/d/1JKIAniL8YkqcFCH88nyPCMC1c33mO8zA/view?usp=sharing)

[Recording video2](https://drive.google.com/file/d/1Uc90YyfhbwzpaEFN7sD8soM_zjymo7if/view?usp=sharing)

## Introduction to Html5:

                         Html5 stands for Hyper Text MarkUp language used to create web pages and the version is 5.
                         Generally web page is divided into 3 parts:
                                       1. Head part(title,Navigation,Meta)
                                       2. Body part(content)
                                       3. Foot part
                         Html5 uses series of elements to display the content,these elements are enclosed with tags.
                         SYNTAX: <STARTTAG> Content </ENDTAG>
                         


#### Different types of Elements in Html5:
                                          1. Block-level Element 
                                              1.1 All heading tags(h1 to h6)
                                              1.2. paragraph tags(p)
                                              1.3. All Semantic Elements
                                          2. Inline Elements
                                              1.1. span tag
                                              1.2. All navigation Elements
                                              1.3. Image tag
                                              1.4. All form-controllers
                                              
                                          3. Navigation Elements(a,href)
                                             1.1. Inbound Navigation(able to navigate to the content in the same page)
                                             1.2. Outbound Navigation(able to navigate to content present in another file)
                                             1.3. mailto(used to send a mail)
                                             1.4. tel(able to call particular person)
