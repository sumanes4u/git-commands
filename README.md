https://sumanes4u.github.io/git-commands/

Be on workingdir and git init 
//git init

//git status

//git add <filename>

//git add -A
All untracked filed to staging area

//git commit -m <message>

//git log --oneline


//git revert HEAD

//git reset --soft <commit ID>

//git reset --hard <commit ID>


//git reset --soft
which will keep your files, and stage all changes back automatically. 

//git reset --hard
 which will completely destroy any changes and remove them from the local directory. Only use this if you know what you’re doing.

Create a new branch
//git checkout -b <dev-branch>

To switch to master branch
//git checkout master

Stay in master branch 
Here dev branches gets merged to master branch
//git merge dev


GIT and GITHUB

//generate SSH keys using 
ssh-keygen

//copy the the public KEY and add into GITHUB
Cat /Users/samarthi/.ssh/id_rsa.pub

GITHUB->setting-> NEW ssh keys

//Local machine perform 
ssh -T git@github.com 



//git push origin
![image](https://user-images.githubusercontent.com/34158104/147390292-88f0f24b-2564-4e62-b674-996465fd1728.png)
