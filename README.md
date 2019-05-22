# UEE THE GITHUB

### install
01. sudo apt-get install git / sudo yum install git

### create ssh-key
01. ssh-keygen -t -C ["email@youremail.com"]
02. cat /home/[YourName]/.ssh/id_rsa.pub

### create and init
01. git config --global user.name ["YourName"]
02. git config --global user.email ["Email@Youremail.com"]
03. mkdir [YourFolder]
04. cd [YourFolder]
05. git init

### pull
01. git remote add [YourRepositoriesName] git@github.com:[YourName/YourRepositories].git
02. git pull --rebase [YourRepositoriesName] master

### push
01. git add [Files] / git add *
02. git commit -m ["input something here about you want"]
03. git push -u [YourRepositoriesName] master / git push [YourRepositoriesName] master

### clone
01. mkdir [NewFolderName]
02. cd NewFolderName
03. git clone git@github.com:[YourName]/[RepositoryName].git
