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