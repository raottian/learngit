git version

cd /…      (新建的文件夹要放的地方）
mkdir 文件名
cd 文件名
pwd     （用于显示当前目录）
git init

git add readme.txt
git commit -m “xxxxxxxxxxxxx”    (提交的同时加上说明文字)

git status      (显示文件的各个状态)
git diff        (显示工作区和暂存区的具体不同，提醒你要add）

git checkout      (用版本库的文件替换工作区，可以用于删除和修改)

工作区——暂存区stage(版本库)——分支(版本库)

//远程库
//创建SSH KEY： ssh-keygen -t rsa -C "youremail@example.com"
//找到ssh文件夹： open ~/.ssh
//GitHub的settings的SSH列表加入id_rsa.pub的内容
//怎么将github中的repository关联到本地的：
git remote add origin git@github.com:raottian/learngit.git
git push -u origin master   (-u是将当前分支推送到远程master分支上，以后可以不加)
//远程库克隆：在要克隆到的文件下输入git clone git@github.com:RogerMonkey/IJCAI_CUP_2017.git