#2013.10.07 add git command document

#git remote
$ git remote -v    // 查看代码库的所有分支

#git pull
$ git pull origin master    //update local code from other branch, like update on svn

#git fetch
$ git fetch origin master:temp
$ git diff temp
$ git merge temp
$ git branch -d temp

#git push
$ git status 
$ git add <file>   (git commit -A  // add all modify files) (git add –i)
$ git commit -m "the notes"    //提交修改
$ git push origin master

#git diff
$ git diff             //查看修改内容
$ git diff --cached    //比较暂存区和版本库之间的区别
$ git diff HEAD        //可以比较工作目录树

#git reset 
$ git reset     // undo the last command

#file manage
$ git mv <原文件名称> <新文件名称>