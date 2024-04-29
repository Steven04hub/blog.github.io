---
title: Jupyter Notebook使用指南
tags:
    - 工具
---

## 1. 安装 Jupyter Notebook

### 1.1 使用 Anaconda 安装

推荐使用 Anaconda 发行版安装 Jupyter Notebook,Anaconda 包含了 Python 和许多常用的科学计算库。

1. 从 [Anaconda 官网](https://www.anaconda.com/products/individual) 下载适用于你操作系统的安装程序。
2. 按照提示完成 Anaconda 的安装。
3. 安装完成后,Jupyter Notebook 就已经包含在内了。

### 1.2 使用 pip 安装

如果你已经安装了 Python,可以使用 pip 命令安装 Jupyter Notebook:

​```bash
pip install jupyter
​```

## 2. 启动 Jupyter Notebook

在终端或命令提示符下输入以下命令:

​```bash
jupyter notebook
​```

这将在默认浏览器中打开 Jupyter Notebook 的界面。

## 3. 创建和编辑 Notebook

### 3.1 创建新的 Notebook

1. 在 Jupyter Notebook 的文件浏览器界面,点击 "New" 按钮。
2. 从下拉菜单中选择 "Python 3" (或你需要的其他内核)。
3. 一个新的 Notebook 将在新标签页中打开。

### 3.2 编辑 Notebook

Notebook 由一系列单元格 (Cell) 组成,每个单元格可以包含代码或 Markdown 文本。

- 要添加新的单元格,可以点击工具栏上的 "+" 按钮,或者在菜单栏中选择 "Insert" > "Insert Cell Below/Above"。
- 要编辑单元格,直接点击单元格进入编辑模式。
- 要运行单元格中的代码,可以点击工具栏上的 "Run" 按钮,或者按下 Shift + Enter 键。

### 3.3 Markdown 单元格

Jupyter Notebook 支持 Markdown 格式的文本。要创建 Markdown 单元格:

1. 插入一个新的单元格。
2. 在单元格的下拉菜单中选择 "Markdown"。
3. 在单元格中输入 Markdown 格式的文本。
4. 运行单元格以渲染 Markdown。

## 4. 保存和导出 Notebook

### 4.1 保存 Notebook

Notebook 会自动定期保存,但你也可以手动保存:

- 在菜单栏中选择 "File" > "Save and Checkpoint"。
- 或者按下 Ctrl + S (Windows/Linux) 或 Cmd + S (macOS)。

### 4.2 导出 Notebook

Jupyter Notebook 支持导出为多种格式,如 HTML、PDF、Markdown 等。

1. 在菜单栏中选择 "File" > "Download as"。
2. 选择你需要的导出格式。
3. 文件将被下载到你的计算机。

## 5. 关闭 Jupyter Notebook

要关闭 Jupyter Notebook:

1. 在文件浏览器界面,勾选你要关闭的 Notebook。
2. 点击 "Shutdown" 按钮。
3. 在终端或命令提示符下按下 Ctrl + C 两次以关闭 Jupyter Notebook 服务器。

## 6. 快捷键
### 命令模式 (按 Esc 键进入)

- `Enter`: 进入编辑模式
- `Shift-Enter`: 运行本单元,选中下个单元
- `Ctrl-Enter`: 运行本单元
- `Alt-Enter`: 运行本单元,在其下插入新单元
- `Y`: 单元转入代码状态
- `M`: 单元转入 Markdown 状态
- `R`: 单元转入 Raw 状态
- `1`: 设定 1 级标题
- `2`: 设定 2 级标题
- `3`: 设定 3 级标题
- `4`: 设定 4 级标题
- `5`: 设定 5 级标题
- `6`: 设定 6 级标题
- `Up`: 选中上方单元
- `K`: 选中上方单元
- `Down`: 选中下方单元
- `J`: 选中下方单元
- `Shift-K`: 扩大选中上方单元
- `Shift-J`: 扩大选中下方单元
- `A`: 在上方插入新单元
- `B`: 在下方插入新单元
- `X`: 剪切选中的单元
- `C`: 复制选中的单元
- `Shift-V`: 粘贴到上方单元
- `V`: 粘贴到下方单元
- `Z`: 恢复删除的最后一个单元
- `D,D`: 删除选中的单元
- `Shift-M`: 合并选中的单元
- `Ctrl-S`: 文件存盘
- `S`: 文件存盘
- `L`: 转换行号
- `O`: 转换输出
- `Shift-O`: 转换输出滚动
- `Esc`: 关闭页面
- `Q`: 关闭页面
- `H`: 显示快捷键帮助
- `I,I`: 中断 Notebook 内核
- `0,0`: 重启 Notebook 内核
- `Shift`: 忽略
- `Shift-Space`: 向上滚动
- `Space`: 向下滚动

### 编辑模式 (按 Enter 键进入)

- `Tab`: 代码补全或缩进
- `Shift-Tab`: 提示
- `Ctrl-]`: 缩进
- `Ctrl-[`: 解除缩进
- `Ctrl-A`: 全选
- `Ctrl-Z`: 复原
- `Ctrl-Shift-Z`: 再做
- `Ctrl-Y`: 再做
- `Ctrl-Home`: 跳到单元开头
- `Ctrl-Up`: 跳到单元开头
- `Ctrl-End`: 跳到单元末尾
- `Ctrl-Down`: 跳到单元末尾
- `Ctrl-Left`: 跳到左边一个字首
- `Ctrl-Right`: 跳到右边一个字首
- `Ctrl-Backspace`: 删除前面一个字
- `Ctrl-Delete`: 删除后面一个字
- `Esc`: 进入命令模式
- `Ctrl-M`: 进入命令模式
- `Shift-Enter`: 运行本单元,选中下一单元
- `Ctrl-Enter`: 运行本单元
- `Alt-Enter`: 运行本单元,在下面插入一单元
- `Ctrl-Shift--`: 分割单元
- `Ctrl-Shift-Subtract`: 分割单元
- `Ctrl-S`: 文件