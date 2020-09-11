# Git 教程

## 1. Git 简介

https://www.liaoxuefeng.com/wiki/896043488029600/896067008724000

### 1.1 Git 诞生

https://www.liaoxuefeng.com/wiki/896043488029600/896202815778784

### 1.2 集中式vs分布式

https://www.liaoxuefeng.com/wiki/896043488029600/896202780297248

### 1.3 安装 Git

参考网址：https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496  

安装完成后，需要最后一步设置，在命令行输入：

```
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

注意 `git config` 命令的 `--global` 参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。

### 1.4 创建版本库

 如果使用Windows系统，为了避免遇到各种莫名其妙的问题，**请确保目录名（包括父目录）不包含中文**。

```
$ mkdir learngit
$ cd learngit
$ git init
$ ls -ah 
```

编辑一个 readme.txt

 ```
$ git add readme.txt	
$ git commit -m "write a readme file"
 ```



