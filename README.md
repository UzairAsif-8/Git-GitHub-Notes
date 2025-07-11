# Git-GitHub-Notes

This is my first repo just made for doing practice and adding necessary notes in Readme.md file.
<br>
We can add HTML tags here to edit like we added br tag to come to next like.
<br>
Now in GitHub there is a thing called comit that means save this version of my code with a message.
<br>
~ this is a tilde symbol in git terminal that is called home directory. It means that we are in root directory
<br>
git config --global user.name "Your Name" //Add a name to you Git
<br>
git config --global user.email "Your Email" //Add your email useful when you are pushing code to github (Email should be same as of GitHub account)
<br>
git config --list //View all the list of configurations
<br>
Now there are two things one is local that means your Laptop and PC and one is Remote that means the files and folders that are on GitHub
<br>
Now there is a command called git clone "link". This clones your gitHub repository in your folder in VScode means we can clone our any github project in our local system
<br>
Now If we want to change our directory like currently we are in GITDEMO folder but we want to go to Git-GitHub-Notes we write cd foldername.
<br>
If we want to see all the files present in that folder we write ls that means list Files
<br>
If we want to see hidden files we want to write ls -a means list all
<br>
To clear a terminal just write clear
<br>
Next is to check the status of the project that how it is working like if we havent changed our file data or we have comitted it then it would show but if we changed or made a new file and didn't comitted it, it would show us modified and other text and to check status we write git status.
<br>
Status in git.....There are four types of status in git. First is untracked (It means that git doesn't recognized that files or new file that git hasn't tracked yet). Second is Modified (It means that you have modified something in that file ). Then comes Unmodified (It means that files are as is is and you haven't modified them yet). The last is staged (Now there are two stages when you add a new file (Means it would show untracked) or change somehting in file (Means it show modified), one is add and one is commit. Now when you dont add it and dont commit it, it is in modified or untracked stage but when you add it it means that now it has passed one stage and now the net is the commit and this stage called staged where the files is done and not comitted yet)
<br>
Now the thing is that how to add changes (Adding means that it sends to staged state...Already stated earlier). To add changes wo write git add filename and it would add changes but if we have lot of files and we have to add all the changes at once we write git "add ." it add all at once and that modified that was appearing red will turn into green means that it is now added
<br>
Now to commit a file we write git commit -m "Some Message". In some message area you write meaning full info of the changes
<br>
Now the changes that we have done here are limited to local like they are not reflecting on GitHub. So to send them to GitHub we write puh command that means to Push local repo content to remote repo (GitHub). So we write git push origin main
<br>
Now if we start making our project from local so now we make a new folder and in order to link our that folder with git we use command git init when we write this while we are in a folder so that folder become a git repo
<br>
Now in order to upload out this Local Git repo in GitHub first we need to make a new repository in GitHub. Then we copy the link of that repo and write a command in git git remote add origin "link of that GitHub Repo". Here the word origin is the name for that link of GitHub Repo. Then we write "git remote -v" and at means that show all the links to which my Local git repo is connected to. Then we can also see in which branch we are by writing command git branch and we can also change the branch name by using git branch -M and then we push our repo to github using command git push origin main
<br>
Then after that we can also add our README.md file and then do same process for that
<br>
Now we can check branch name with git branch and we can change branch name with git branch -m branch-name. Now if we want to make a new branch and switch to it we write a command git checkout -b new-branch-name and then we will be directed to that new branch and if we want to switch to a branch we write git checkout branch-name
<br>
Now if we want to delete a branch we write git branch -d branch-name and it would delete a branch but remember that you cannot delete a branch that you are already in first you have to go to another branch using git chrckout branch-name and then we can delete that
<br>
If you want to push your branch so you will write git push origin "That specific branch name"
<br>
If you have two branches and you are working on a same file that other branch has so you cannot switch to other branch without adding and commenting those changes in the present branch and same you cannot push to another branch while staying in another until and unless you have fully commited that specific branch.
<br>
Now if you are in branch and you have made changes to the file in that branch and other branch has also same file so you cannot switch to another branch without commiting it but wait here is another way that is called stashing. In this when you write git stash it temporaily hides those changes and now you can switch to another branch and when you come back you can simply write git stash pop and there you go.... on the same stage that you were before.......Imagine you're writing a LETTER, but suddenly you need to attend a meeting (switch branch). You don’t want to save it fully (commit), but also don’t want to throw it away.
So, you fold the paper, put it in your drawer (stash), go to the meeting, then come back and pull it out again (stash pop).
<br>
Now if we want to see the difference between two branches we can compare them by using git diff branch-name
<br>
Now if you want to merge two branches there are two methods first is the pull request on github and second is the git merge branch-name command and after merging if you want to delete branch write git branch -d "Branch-name" and that branch would b=get deleted and then write git fetch -p and with this will remove all the references of the remote deleted branches
<br>
Now if you want to see the changes that happened in github when you merged by pull request you need to write git pull origin main and this will pull all the changes and details
