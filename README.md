This is a repo for learning git! 


1. cd to proper directory. mkdir. cd into new folder 
2. git init 
3. ls -a to see if new directory is listed with .git 

4. create a new file 
5. git add . 
6. git status to see 
7. git commit -m"message"
8. git log will show the commit history 

9. create a new repo in github 


10. connecting a local repo : 

git remote add origin YOUR-GITHUB-LINK-HERE
git branch -M main
git push -u origin main

    git remote add origin YOUR-GITHUB-LINK-HERE adds a reference from your local git repo to your Github repo. We gave this reference a name: origin. So now we can perform commands like git pull origin and git knows to go to that Github link and pull changes from that repository.

    git branch -M main renames our default branch to main instead of master (the previous default).

    git push -u origin main pushes the local changes on our repo over to Github. Our two repositories should now be in sync.