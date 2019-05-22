## 全局设置
01. git config --global user.name "seedcm"
02. git config --global user.email "seedcm@163.com"


## 创建仓库(如果未通过README.md或其方方式初始化)
01. mkdir test_folder
02. cd test_folder
03. git init

// 添加README.md文件
04. touch README.md
04. vim README.md

05. git add README.md
06. git commit -m "first commit"
07. git remote add gitee https://gitee.com/seedcm/test.git
07. git remote add gitee git@gitee.com:seedcm/test.git
07. git remote add github https://github.com/seedcm/test.git
07. git remote add github git@github.com:seedcm/test.git
08. git push -u gitee master
08. git push -u github master


## PULL
01. mkdir test_folder
02. cd test_folder
03. git init
04. git remote add gitee https://gitee.com/seedcm/test.git
04. git remote add gitee git@gitee.com:seedcm/test.git
04. git remote add github https://github.com/seedcm/test.git
04. git remote add github git@github.com:seedcm/test.git
05. git pull --rebase gitee master
05. git pull --rebase github master


## PUSH
01. git add test.c
01. git add test.c test1.c test2.c ...
01. git add *
02. git commit -m "update"
03. git push -u gitee master
03. git push -u github master


## CLONE
01. mkdir test_folder
02. cd test_folder
03. git init
04. git clone https://gitee.com/seedcm/test.git
04. git clone git@gitee.com:seedcm/test.git
04. git clone https://github.com/seedcm/test.git
04. git clone git@github.com:seedcm/test.git


## REMOTE
01. mkdir test_folder
02. cd test_folder
03. git init

// 为当前test_folder仓库添加远程gitee/github仓库地址
01. git remote add gitee https://gitee.com/seedcm/test.git
01. git remote add gitee git@gitee.com:seedcm/test.git
01. git remote add github https://github.com/seedcm/test.git
01. git remote add github git@github.com:seedcm/test.git

// 为当前folder仓库删除远程gitee/github仓库地址
01. git remote rm gitee
02. git remote rm github

// 查看当前test仓库地址的远程仓库信息
01. git remote -v


## ADD
01. git add test_file.c
01. git add test_file01.c test_file02.c test_file03.c test_file04.c ...
01. git add *


## COMMIT
01. git commit -m "update"

