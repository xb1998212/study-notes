# Linux 常用命令速查表 / Linux Cheat Sheet

## 文件与目录操作 / File & Directory Operations
- `ls` —— 列出当前目录内容 / list directory contents
- `ls -la` —— 列出所有文件（含隐藏），显示详细信息 / list all with details
- `cd <目录>` —— 切换目录 / change directory
- `pwd` —— 显示当前路径 / print working directory
- `mkdir <目录名>` —— 创建新目录 / make directory
- `touch <文件名>` —— 创建空文件 / create empty file
- `cp <源> <目标>` —— 复制文件或目录 / copy
- `mv <源> <目标>` —— 移动或重命名 / move or rename
- `rm <文件名>` —— 删除文件 / remove file
- `rm -r <目录名>` —— 递归删除目录（慎用！）/ remove directory recursively
- `cat <文件名>` —— 查看文件内容 / view file content

## 系统与权限 / System & Permissions
- `sudo <命令>` —— 以超级用户权限执行 / execute as superuser
- `chmod 755 <文件名>` —— 修改文件权限 / change file permissions
- `chown <用户> <文件名>` —— 修改文件所有者 / change file owner
- `ps aux` —— 查看所有运行进程 / view all running processes
- `kill <PID>` —— 终止进程 / kill process by ID
- `df -h` —— 查看磁盘空间（人类可读）/ view disk space (human-readable)
- `free -m` —— 查看内存使用（MB）/ view memory usage (MB)

## 网络相关 / Networking
- `ping <IP或域名>` —— 测试网络连通性 / test network connectivity
- `curl <URL>` —— 发送 HTTP 请求 / send HTTP request
- `wget <URL>` —— 下载文件 / download file
- `ifconfig` 或 `ip a` —— 查看网络接口信息 / view network interfaces

## 压缩与归档 / Compression & Archive
- `tar -czvf <压缩包名>.tar.gz <目录>` —— 创建 tar.gz 压缩包 / create tar.gz archive
- `tar -xzvf <压缩包名>.tar.gz` —— 解压 tar.gz / extract tar.gz
- `zip -r <压缩包名>.zip <目录>` —— 创建 zip 压缩包 / create zip archive
- `unzip <压缩包名>.zip` —— 解压 zip / extract zip

## 常用组合技巧 / Useful Shortcuts
- `Ctrl + C` —— 终止当前命令 / interrupt current command
- `Ctrl + Z` —— 暂停当前命令 / suspend current command
- `Tab` 键 —— 自动补全路径 / auto-complete path
- `↑` / `↓` 方向键 —— 切换历史命令 / navigate command history
- `history` —— 查看命令历史 / view command history