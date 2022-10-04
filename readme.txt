Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.
工作区---暂存区---版本库
command list:
git config --list
git add
git commit -m "explanation"
git status
git diff
git log --pretty=oneline
git reset --hard HEAD^ # HEAD指向当前版本
git reflog # 记录每次命令
git checkout -- <file> # 返回到上一个提交的状态
git reset HEAD <file> # 将修改从暂存区退回到工作区
git rm <file> # 从版本库删除文件，然后需要在提交
git push # 推送到远程库
git clone
git remote rm <name> # 删除远程库
git remote -v # 查看远程库信息
mv mygit <new directory> # 修改本地库名
git remote add origin <url> # 第一次同步到GitHub
git branch -M main
git push -u origin main