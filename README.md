# Git-GitHub-Notes

This is my first repo just made for doing practice and adding necessary notes in Readme.md file.
<br>
We can add HTML tags here to edit like we added br tag to come to next like.
<br>
Now in GitHub there is a thing called comit that means save this version of my code with a message.
<br>
~ this is a tilde symbol in git terminal that is called root directory. It means that we are in root directory
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
If we want to see hidden files we want to write ls --a means list all
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
