# gitcommand

git init 初始化git
git add *.c 添加文件到git
git commit -m 'initial project version' 提交
git clone https://github.com/ 克隆项目
git clone https://github.com/ mylibgit 克隆并重命名
git status  检查当前文件状态
git status -s 命令或 git status --short 命令，你将得到一种更为紧凑的格式输出
git diff 查看尚未暂存的文件更新了哪些部分
git diff --cached 查看已经暂存起来的变化
git rm 移除文件
git mv file_from file_to 移动文件
git log 查看提交历史
git remote 查看远程仓库
git remote add <shortname> <url> 添加一个新的远程 Git 仓库
git fetch [remote-name]从远程仓库中抓取与拉取
git push [remote-name] [branch-name] 推送到远程仓库
git remote show [remote-name] 查看远程仓库
git remote rename oldname newname 修改一个远程仓库的简写名
git remote rm  remotename 移除一个远程仓库
git tag 列出标签
git checkout -b [branchname] [tagname] 在特定的标签上创建一个新分支
git config 设置一个别名
git branch [-d] branchname 分支创建[删除分支]
git checkout  branchname 分支切换
git merge branchname 将branchname分支和当前分支合并
git ls-remote (remote) 来显式地获得远程引用的完整列表
git remote show (remote) 获得远程分支的更多信息
git fetch origin 查找 “origin” 是哪一个服务器，从中抓取本地没有的数据，并且更新本地数据库，移动 origin/master 指针指向新的、更新后的位置。
git push (remote) (branch) 推送
