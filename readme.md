this is a md file
🌱 Understanding Branches & main in Git (Real-Life Scenarios)
git is used to track changes in the codebase
while github is a cloudplatform to store your repositories
concept of remote :
local repo : git init creates a local repo
remote repo: stored on github/gitlab
to connect to github , to have to connect your project to remote
while creating a repo you come across this : https://github.com/bhabanikantpra2003/mastering_git.git , this is a remote
how to use this : write git remote add origin link
from this intead to typing the repo url everytime we can use the 'origin' keyword everytime , we can have multiple repos , just name them other than origin , because it is already taken

git push -u origin main
git branch branch-name
git checkout branch-name
git checkout main
to create and then move to that branch in one line : git checkout -b branch-name

task
create a new branch
move to that branch
change the readme file
commit to the orinal code in the github

this thing will be channged in the feature branch and not in the main branch
see the task is completed , now the feature branch has all the code and the readme file in the main branch have just the "this is a md file content" , beacause we updated all this in the branch name feature-branch

command
git branch feature-branch
git checkout featrue-branch
updated the content
git add ./
git commit -m "message-here"
git push -u origin feature-branch

now every time you can just write git push ,, instead of writing push -u origin ...
also for downloading the latest code from the remote file to local file use :
git pull

Now how to merge this change to the main branch , beacuse the main branch still says "this is a md file"

to do this we need a pull request , it lets you share your changes with your team and get it reviewed , once approved , your code becomes part of the main branch , keeping the code stable and organized

you can do it manually as well as code , we will do it manually
