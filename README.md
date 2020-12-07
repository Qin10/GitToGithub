
# GitToGithub<br/>
使用Git远程操作仓库<br/>
​## 操作步骤<br/>
1、创建命名文件夹<br/>
2、在该文件夹中单击鼠标右键 点击Git Bash Here<br/>
3、在命令行通过以下命令设置用户的git名字与邮箱：<br/>
    git config --global user.name 'username' (_username与github用户名相同_)<br/>
    git config --global user.email 'yourEmail' (_yourEmail与github注册的邮箱相同_)<br/>
    PS：*由于Git是分布式版本控制系统，所以每个机器都必须“自报家门”*<br/>
4、在命令行中键入：<br/>
    git init (_初始化git库，生成.git文件_)<br/>
5、在github仓库主页左键单击**code下载按钮**复制**仓库链接**<br/>
6、在命令行键入以下命令来在本地电脑克隆github仓库：<br/>
    git clone https://github.com/Qin10/GitToGithub.git (_可在命令行右键点击paste复制链接_)<br/>
7、在命令行键入以下linux命令来新建想要传入github仓库的文件：<br/>
    touch filename (_直接右键新建文件也可_)<br/>
8、在命令行键入以下linux命令来修改文件：<br/>
    vi filename (_或直接在编译器中编辑文件也可_)<br/>
9、在命令行键入：<br/>
    git add filename (_将工作区文件导入暂存区_)<br/>
10、在命令行键入：<br/>
    git commit -m 'description' (_将暂存区文件导入git仓库，单引号中添加操作说明_)<br/>
11、在命令行键入：<br/>
    git push (_将git仓库文件远程导入github仓库，若系统缓存没有保存用户登录信息，需要通过github验证_)<br/>
12、刷新github仓库主页，若出现用户添加文件信息则操作成功~<br/>
