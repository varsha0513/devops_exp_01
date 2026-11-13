Code – 
ex.py 

print("Welcome to Git") 
print("Git tracks code changes") 

Code – ex1.py 
print("Welcome to GitHub") 
print("My first DevOps experiment") 
Git commands 

git config --global user.name "Your Name" 
git config --global user.email "your_email@gmail.com" 

git init 
git status 
git add . 
git commit -m "initial commit" 
git log 
git branch -M main 
git remote add origin https://github.com/USERNAME/ex1.git 
git remote -v 
git push -u origin main 


git checkout -b main1 

# Modify ex.py, then run: 
git add . 
git commit -m "updated file" 
git push origin main1