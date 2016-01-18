# Git-command
Git命令行笔记
1、关联 SSH
2、github上创建库
3、Github和本地git关联
  git remote add  [origin]  [git项目地址]
4、本地提交
  git push [origin] master

-------------------------------------------

a、也可以远程克隆
  git clone [地址]
b、创建分支dev  然后切换至dev分支
  git checkout -b dev
  用git branch 命令查看当前分支
    bit branch
c、修改后在dev分支上提交
  git add readme.txt
  git commit -m 'blabla'
d、现在dev分支完成，切换回master分支
  git checkout master
  然后合并
   git merge dev
  删除dev
    git branch -d dev
