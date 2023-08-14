## Github Commend doc

### 1. Git Bash Start

- git config --global user.name "Name"
- git config –-global user.email "Email Address(Same as Git hub)"
- git config --list

### 2. Make SSH Key
- ssh-keygen.exe  

### 3. Git Commend

- git init 
- git add .
- git commit -m "first commit"

**1. Repository**
- git remote add origin "gitaddress"
- git remote –v

**2. Push & Pull**
- git push -u origin main
- git pull origin main

**3. Branch**
- git branch -M main 
- git checkout –b freshman
- git switch main

**4. File Delete in Repository**
- git rm "filename"  : Delete local & Repository
- git rm --cached "filename"  : Delete Repository Only
