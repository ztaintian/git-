## git 常用命令 
1、git本地创建分支  

    git branch  新分支名  或 git checkout -b 新分支名

2、git本地创建分支提交远程  

    git push --set-upstream origin 分支名  

3、git拉取远程分支  

    git checkout -b 本地分支名 origin/远程分支名

4、git master合并代码到分支上   

    -首先切换到主分支

    git checkout master

    使用git pull 把领先的主分支代码pull下来

    git pull

    切换到自己的分支

    git checkout xxx(自己的分支)

    把主分支的代码merge到自己的分支

    git merge master

    git push推上去ok完成,现在 你自己分支的代码就和主分支的代码一样了

