# 🧪 Git & GitHub Practice Steps

#### This document outlines the Git operations. These are structured steps to understand how Git works locally and with GitHub.
</br>
</br>
</br>

<div align="center">

# **🔧  Git Hands-on**
</div>

</br>



### ⚠️ Prerequisites
#### install git and gitlab 
apt install git -y && apt install gh -y 


#### create tokan in github (copy and secure to a text editor) 


#### Set up Git username and email globally 
git config --global user.name parthraj \
git config --global user.email parthraj.learn@gmail.com 

</br>

# TASK-1 📋
#### create local repo 
<pre>mkdir directory
cd directory
git init 
create a file 
git add file
git commit -m "xyz" filename
git push -u origin branch-name
</pre>
</br>

# TASK-2 📋
#### create repo in github & clone it to local 
<pre>git clone url 
create a file 
git add file
git commit -m "xyz" filename
git push -u origin branch-name
</pre>
</br>
    
# TASK -3 📋
#### create a branch & delete file
<pre>git checkout branch-name
git rm filename      
git commit -m "xyz" filename
git push -u origin branch-name
</pre>
</br>

# TASK -4 📋
### change the branch & delete the branch 
<pre>git chekout branchname
git branch
create a file 
git add file
git commit -m "xyz" filename
git push -u origin branch-name
git push origin --delete branch-name
</pre>
</br>

# TASK -5 📋  
### clone the diffent branch & pull a branch
<pre>git clone -b branch-name url 
git branch
git pull orgin branch-name
git branch 
create a file 
git add file
git commit -m "xyz" filename
git push -u origin branch-name    
</pre>
</br>
   
# TASK -6 📋     
###  merge the new branch to main branch 
<pre>git checkout main
git pull origin main
git branch
git merge origin new-branch
</pre>
</br>

# TASK -7 📋
### create github repo form local
<pre>apt install gh -y </br>
gh auth login
git remote add origin https://github.com/2002-parthraj/reponame.git
gh repo create reponame --public --source=. --remote=origin --push
</pre>




