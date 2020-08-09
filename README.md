# devops-course

Git basic commands to create a working directory and push the changes to remote from local.

Steps to be followd and the respective commands:

1.Initial configuration to be done at local system :
git config --global user.name "XXX"
git config --global user.email XXX@example.com

2.create a working directory.

3.Inititalize git to the directory.
git init

4. Add the files part of your development.
git add .

5. Check the status
git status

6. commit the changes.
git commit -m "msg"

7.create repo in git to sync repositories.
git remote add origin "https://github.com/snehalathaYeleswarapu/devops-course.git"
git push origin master 
(enter the credentials to push changes globally from local system)
