# github的使用
## pycharm代码上传到github的配置工作
1. 安装git
2. github设置添加SSH Key，git绑定用户名和邮箱
3. 验证是否成功
4. pycharm设置中的version control的github输入用户名和密码，git输入git可执行程序的路径

## pycharm代码上传github
1. VCS下的import into Version Control，选Share Project on Github，设置好点share，选中项目中要上传的文件即可
2. 更新本地代码到github，需要点VCS下的commit，出现的框左上角是需要提交的内容，左中是输入描述，再下是与之前的不同之处，点commit；再在VCS中找git，push即可。

## 查看github的历史提交版本，并定位到历史版本
1. 打开项目，点x commits
2. 点想看的历史版本右侧的<>
3. download代码，注意clone下来的是最新版本，zip是历史版本

## 从github仓库clone项目
1. 在本地建好存放项目的文件夹
2. 在文件夹下鼠标右键Git Bash Here
3. 输入git init初始化git
4. 去github复制要clone的仓库的https地址
5. 输入git clone https地址即可