# Git Practice

[Git and Github video](https://www.youtube.com/watch?v=RGOj5yH7evk).


## Repository first created on github  

1. Created the demo file on github and cloned it on my laptop - 
**git clone address of repo**

2. Made changes locally, track the changes by - 
**git status**

3. Created a new file git was not able to track it, git will be able to track it if we add it - 
**git add file name or git add add . (tracks all new file added)**

4. Now we have to commit the changes - 
**git commit -m "This is for Title and the other is description" -m "this makes the changes in the git repo"**

5. Now to upload the changes to github you have to push it - 
**git push**

6. To make changes to github repo from local computer you have to prove to github that you are the ownwer so that you can push changes
using **SSH keys**

7. You need to generate a ssh key - 
**ssh-keygen -t rsa -b 4096 -C "email@example.com"** 

8. To find the key -**ls | grep keyname**

9. Now you have to upload this keyname.pub to github after this you have to add the ssh key to ssh agent -
**- 1. eval "$(ssh-agent -s)"** 
**- 2. Now copy paste the key**
**- 3. ssh-add ~/.ssh/keyname**

10. Lastly we can push on github after origin specifies the name of branch -
**git push origin main**


## Repository created first on Local computer



