# scriptcn

创建一个新的repository


cd ~/scriptcn

git init

git add .

git commit

git remote add https://github.com/scriptcn/scriptcn.github.io.git

git push origin master

2.更新项目（新加了文件）：
 
$cd ~/hello-world
 
$git add . //这样可以自动判断新加了哪些文件，或者手动加入文件名字
 
$git commit //提交到本地仓库
 
$git push origin master //不是新创建的，不用再add 到remote上了
 
3.更新项目（没新加文件，只有删除或者修改文件）：
 
$cd ~/hello-world
 
$git commit -a //记录删除或修改了哪些文件
 
$git push origin master //提交到github
 
4.忽略一些文件，比如*.o等:
 
$cd ~/hello-world
 
$vim .gitignore //把文件类型加入到.gitignore中，保存
 
然后就可以git add . 能自动过滤这种文件
 
5.clone代码到本地：
 
$git clone https://github.com/scriptcn/scriptcn.github.io.git
 
假如本地已经存在了代码，而仓库里有更新，把更改的合并到本地的项目：
 
$git fetch origin //获取远程更新
 
$git merge origin/master //把更新的内容合并到本地分支
 
6.撤销
 
$git reset
 
7.删除
 
$git rm * // 不是用rm
 
//——————————常见错误———————————–
 
1.$ git remote add origin https://github.com/scriptcn/scriptcn.github.io.git
 
错误提示：fatal: remote origin already exists.
 
解决办法：$ git remote rm origin
 
然后在执行：$ git remote add origin https://github.com/scriptcn/scriptcn.github.io.git 就不会报错误了
 
2. $ git push origin master
 
错误提示：error:failed to push som refs to
 
解决办法：$ git pull origin master //先把远程服务器github上面的文件拉先来，再push 上去。


