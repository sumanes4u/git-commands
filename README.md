# git-commands
git cheat sheet

//git init

//git status

//got add 

//git add -A
All untracked filed to staging area

//git commit -m <message>

//git log --oneline


//git revert 


git reset --soft, which will keep your files, and stage all changes back automatically. git reset --hard, which will completely destroy any changes and remove them from the local directory. Only use this if you know what you’re doing.

Create a new branch
//git checkout -b <dev-branch>

To switch to master branch
//git checkout master

Stay in master branch 
Here dev branches gets merged to master branch
//git merge dev


GIT and GITHUB

//generate SSH keys using 
Ssh-keygen

//copy the the public KEY and add into GITHUB
Cat /Users/samarthi/.ssh/id_rsa.pub

GUTHUB setting NEW ssh keys

//Local machine perform 
ssh -T git@github.com 
![image](https://user-images.githubusercontent.com/34158104/147388926-55e5b84e-9e9e-44fb-9cab-7bd43bfb5a9c.png)
