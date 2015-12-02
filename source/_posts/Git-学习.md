title: Git 学习
date: 2015-12-02 10:04:22
tags:
---
## 一、提交项目到仓库
- 初始化仓库

     git init

- 添加文件到暂存区

     git add [文件]

- 添加提交信息

     git commit -m "first commit"

- 添加项目到远程仓库
  
     git remote add origin [远程仓库地址]

- 上传本地分支代码

     git push origin master

## 二、克隆仓库

     git clone [远程仓库地址]
     
     git clone [远程仓库地址] [自定义项目名称]

## 三、其他命令

- 查看远程仓库名

     git remote

- 查看远程仓库地址信息

     git remote -v

- 远程仓库重命名

     git remote rename origin [修改后名称]

- 查看当前文件状态

     git status

## 四、分支

- 创建分支

     git branch [分支名]

- 查看所有分支

     git branch -a

- 查看本地分支

     git branch

- 将本地分支提交到远程分支

    git push origin [分支名]

- 切换分支

    git checkout [分支名]

- 重命名本地分支

    git branch -m [命名前] [命名后]

- 删除本地分支

    git branch -d [分支名]

- 删除远程分支

    git push --delete origin [分支名]

## 五、fetch

- 远程仓库跟新时，将这些更新取回到本地

    git fetch [远程仓库名]

- 取回某个分支
  
    git fetch [远程仓库名] [分支名]

## 六、pull 

- 取回远程仓库的某个分支，在与本地分支合并

    git pull [仓库名] [远程分支名] [本地分支名]

- 如果当前只有一个分支
  
    git pull

## 七、push

- 将本地分支更新提交到远程仓库

    git push [远程仓库名] [远程分支]：[本地分支]

-如果远程仓库分支与本地分支名称相同
  
    git push origin [仓库名]

- 如果当前只有一个分支

    git push 
  


    




   



     





