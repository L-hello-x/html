# html
学习过程

一、git常用命令

1.查看文件状态
git status

2.UI 查看
gitK

3.拉取远程仓库代码
git pull

4. 克隆仓库代码
git clone 仓库地址

5. 跟踪所有变动过的文件
git add '文件名'

或者
git add .   所有文件

6.本地提交

git commit -m '提交描述'

7. 推送到远程仓库
git push 

8. 修改冲突

9. 创建分支
git  branch 分支名


10 .撤销提交  恢复到某个版本
     回退某个版本：查询需要回退的commit记录
        git  log
           查看commitId
        也可以通过Ui查看 gitk 来看
     软恢复：
        git reset --soft commitID
     硬恢复:
        git reset --hard commitID

11. 修改git 邮箱 密码
git config --global user.name
git config --global user.email