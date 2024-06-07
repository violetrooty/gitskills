# gitskills

快照在Git中被称为`commit`

`git checkout -- file`可以丢弃工作区的修改

###### 版本回退

`git reset --hard HEAD^`

`git reset --hard 1094a`

`git reset`命令既可以回退版本，也可以把暂存区的修改回退到工作区

`git log`可以查看提交历史

`git reflog`查看命令历史

###### 分支

查看分支：`git branch`

创建分支：`git branch <name>`

切换分支：`git checkout <name>`或者`git switch <name>`

创建+切换分支：`git checkout -b <name>`或者`git switch -c <name>`

合并某分支到当前分支：`git merge <name>`

查看分支合并情况：git log --graph --pretty=oneline --abbrev-commit

删除分支：`git branch -d <name>`





