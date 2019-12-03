#学习git的第一天
mkdir  learngit //创建新仓库

pwd //查看当前目录

git init //这个目录变成Git可以管理的仓库

$ git add readme.txt  //添加文件到仓库

git commit -m "???"  //把文件提交到仓库

git status //查看仓库当前的状态

git diff  readme.txt //查看修改

git log //查看历史记录

git reset  //版本回退

cat readme.txt //查看 readme.txt 文件的内容

git checkout -- readme.txt //readme.txt文件在工作区的修改全部撤销

rm test.txt //删除文件

git checkout -- test.txt //用版本库里的版本替换工作区的版本

git remote add origin git@github.com:??? /???.git//关联远程仓库

git push -u origin master  //第一次推送到远程仓库

git push origin master //非首次推送

git clone <版本库的网址>

$ git remote –v参看远程主机的网址
```
