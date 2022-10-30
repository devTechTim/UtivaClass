# UtivaClass
Github Lesson  
##introduction on  how to push from  local environment to github  
Downloaded Gitbash (https://git-scm.com/downloads)  
#CONFIGURE GITBASH  
git config --global user.name "name"  
git config --global user.email "email"  
#WORKING WITH THE CONFIGURED ENVIRONMENT  
mkdir website  
cd website  
git init  
touch index.html  
#CLONE YOUR GITHUB REPO  
git remote add origin "url (from the HTTPS tab of the repo's CODE)"  
#PUSH TO GITHUB  
git add index.html  
git commit -m "DESCRIPTION"  
git push origin master  
