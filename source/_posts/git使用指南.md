---
title: Git使用指南
tags:
    - 工具
---

## 1. 安装与配置

### 1.1 安装Git

- Windows: 从 [Git官网](https://git-scm.com/download/win) 下载安装程序,按照提示完成安装。
- macOS: 使用 Homebrew 安装,在终端输入 `brew install git`。
- Linux: 使用包管理器安装,例如在 Ubuntu 上,输入 `sudo apt-get install git`。

### 1.2 配置用户信息

安装完成后,在终端输入以下命令配置用户名和邮箱:

​```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
​```

## 2. 基本操作

### 2.1 创建仓库

在项目目录下,使用以下命令初始化 Git 仓库:

​```bash
git init
​```

### 2.2 添加文件到暂存区

使用以下命令将文件添加到暂存区:

​```bash
git add filename
​```

或者添加所有文件:

​```bash
git add .
​```

### 2.3 提交更改

使用以下命令将暂存区的更改提交到仓库:

​```bash
git commit -m "Commit message"
​```

### 2.4 查看仓库状态

使用以下命令查看当前仓库的状态:

​```bash
git status
​```

### 2.5 查看提交历史

使用以下命令查看提交历史:

​```bash
git log
​```

## 3. 分支管理

### 3.1 创建分支

使用以下命令创建新分支:

​```bash
git branch branch_name
​```

### 3.2 切换分支

使用以下命令切换到指定分支:

​```bash
git checkout branch_name
​```

### 3.3 合并分支

使用以下命令将指定分支合并到当前分支:

​```bash
git merge branch_name
​```

## 4. 远程仓库

### 4.1 添加远程仓库

使用以下命令添加远程仓库:

​```bash
git remote add origin repository_url
​```

### 4.2 推送到远程仓库

使用以下命令将本地仓库的更改推送到远程仓库:

​```bash
git push -u origin branch_name
​```

### 4.3 从远程仓库拉取更改

使用以下命令从远程仓库拉取更改:

​```bash
git pull origin branch_name
​```

## 5. 其命令

- `git clone repository_url`: 克隆远程仓库到本地。
- `git diff`: 查看文件的更改内容。
- `git stash`: 暂存当前工作区的更改。
- `git stash pop`: 恢复最近一次暂存的更改。
- `git reset`: 撤销提交或暂存的更改。
- `git rebase`: 变基,用于合并多个提交或调整提交顺序。
