# Git Introduce
git 基础使用介绍

## Git 起步

#### 版本控制系统（VCS）

- ###### 本地版本控制系统（Local VCS）

- ###### 集中式版本控制系统（Centralized VCS）eg：SVN

- ###### 分布式版本控制系统（Distributed VCS）eg：Git

#### Git 历史

## Git 基础

#### 基础

- ###### 直接记录快照，而非差异比较

- ###### 近乎所有操作都是本地执行

- ###### Git 保证完整性

- ###### Git 一般只添加数据

#### 三种状态

- ###### 已提交（committed）

  - ###### 表示数据已经安全的保存在本地数据库中

- ###### 已修改（modified）

  - ###### 表示修改了文件，但还没保存到数据库中

- ###### 已暂存（staged）

  - ###### 表示对一个已修改文件的当前版本做了标记，

#### 三个工作区域

![areas](/Users/andywu/Desktop/areas.png)

- ###### Git 仓库（.git directory（Repository））

- ###### 工作目录（Working Directory）

- ###### 暂存区域（Staging Area）

#### 工作流程

1. ###### 在工作目录中修改文件。

2. ###### 暂存文件，将文件的快照放入暂存区域。

3. ###### 提交更新，找到暂存区域的文件，将快照永久性存储到 Git 仓库目录。

#### 四种文件状态

![lifecycle](/Users/andywu/Desktop/lifecycle.png)

- ###### 未跟踪（Untracked）

- ###### 未修改（Unmodified）

- ###### 已修改（Modified）

- ###### 已暂存（staged）

#### 基础操作

- ###### Git 命令

  - ###### command + [--options] + [arguments]


- ###### 获取 Git 仓库

  - ###### git init - Create an empty Git repository or reinitialize an existing one

  - ###### git clone - Clone a repository into a new directory


- ###### 记录每次更新到仓库

  - ###### git status - Show the working tree status

  - ###### git add - Add file contents to the index

  - ###### git commit - Record changes to the repository

- ###### 撤销操作

  - ###### git reset - Reset current HEAD to the specified state

    - ###### git reset HEAD

      - ###### HEAD

  - ###### git revert - Revert some existing commits

  - ###### git chekout - Switch branches or restore working tree files

- ###### 远程仓库的使用

  - ###### git clone

  - ###### git remote - Manage set of tracked repositories

    - ###### git remote -v

    - ###### git remote rename branchName newBranchName

  - ###### git fetch - Download objects and refs from another repository

## Git 命令

- ###### git branch - List, create, or delete branches


- ###### git merge -  Join two or more development histories together

- ###### git rebase - Reapply commits on top of another base tip

- ###### git-tag - Create, list, delete or verify a tag object signed with GPG