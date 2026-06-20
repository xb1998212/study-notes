# Git 常用命令速查表

## 配置
- `git config --global user.name "用户名"`
- `git config --global user.email "邮箱"`

## 基础操作
- `git clone <仓库地址>` —— 下载仓库到本地
- `git add .` —— 暂存所有改动
- `git commit -m "备注"` —— 提交
- `git push` —— 推送到云端
- `git pull` —— 拉取最新代码
## 分支管理 / Branch Management
- `git branch` —— 查看所有分支 / list all branches
- `git branch <分支名>` —— 创建新分支 / create a new branch
- `git switch <分支名>` —— 切换到指定分支 / switch to a branch
- `git merge <分支名>` —— 合并分支到当前分支 / merge a branch into current
- `git branch -d <分支名>` —— 删除分支 / delete a branch

## 撤销与回退 / Undo & Rollback
- `git status` —— 查看当前状态 / check current status
- `git log` —— 查看提交历史 / view commit history
- `git reset HEAD~1` —— 撤销最后一次提交（保留改动） / undo last commit (keep changes)
- `git reset --hard HEAD~1` —— 撤销最后一次提交（丢弃改动） / undo last commit (discard changes)
- `git restore <文件名>` —— 丢弃工作区的改动 / discard changes in working directory

## 远程操作 / Remote Operations
- `git remote -v` —— 查看远程仓库地址 / view remote repo URLs
- `git push origin <分支名>` —— 推送到指定分支 / push to a specific branch
- `git pull origin <分支名>` —— 拉取指定分支的更新 / pull updates from a branch