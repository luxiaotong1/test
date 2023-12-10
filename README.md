# gitlab项目代码提交
一、项目介绍

二、安装git
1、下载git安装包并安装；
2、进入计划存放资源的文件夹，以下以 “E:\gitlab”为例；
3、右键单击“Git Bash Here”，打开Git Bash；
4、输入“git config --global user.name "XXX" ”配置本地用户名，其中XXX替换为自己的账户名；
5、输入“git config --global user.email "XXX" ”配置本地用户邮箱，其中XXX替换为自己的邮箱；

三、配置git本地库
1、输入“git clone http://xxx”。
2、输入“cd xxx”进入xxx的本地文件夹；
3、输入“git switch -c main”创建并进入本地“main”分支；
4、输入“git pull origin main”获取远程“main”分支的内用，合并进本地“main”分支。

四、常用基本操作
1、“git add .  ”添加当前子目录下所有修改过的文件到index暂存区；
2、“git commit -m "XXX" ”提交index中的修改，XXX为针对本次修改的描述；
3、“git push origin main”将当前修改内容提交至远程库中；
4、“git switch -c XXX”切换至本地XXX分支，如果XXX分支不存在则创建并切换至XXX分支，注意如远程仓库没有XXX分支，提交文件时会报错。

五、其他操作详细指南
https://www.runoob.com/note/56524
https://www.runoob.com/git/git-tutorial.html
https://zhuanlan.zhihu.com/p/428744590
