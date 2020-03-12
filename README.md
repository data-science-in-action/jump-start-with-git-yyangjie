# jump-start-with-git-yyangjie
jump-start-with-git-yyangjie created by GitHub Classroom

In my first assignment,I learned the following:
For git :
Git Is the most advanced version control system in the world.
Some basic commands:
To know who are you 
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
To creat a local repository and add and commit some files
$ mkdir learning 
$ cd learning
$ touch first.txt
$ git init# which you can manage the git's repository 
$ git add
$ git commit -m "initial commit"

For github:
To create a remote repository and push your code from the local repo to the remote
#Firstly ,you should head to GitHub and create a repository
#Secondly,in your terminal type 
$ git remote add origin URL_OF_YOUR_REPO
$ git push -u origin master
To create an SSH key
$ ssh -T git@github.com 
