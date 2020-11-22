# git 常用命令 
1. 本地初始化，在本地该目录下新建git文件，记录版本分支等信息
> git init

2. 连接远端仓库
> git remote add origin git@github.com:plumrx/book-report.git

3. 同步远端仓库代码远端的分支是 main 
> git pull origin main 

4. 设置远端分支 main 对应本地分支 master 
> git branch -u origin/main master

5. 向远端库推代码
> git push origin HEAD:main