# 安装
1. 下载地址 https://git-scm.com/downloads

### 远端
1. hithub https://github.com/  开源(分享代码)
2. gitlab (需要自己搭建环境)  私有

### 创建git仓库
1. Public 开源
2. Private 私有

### 使用git 
1. 直接在本地初始化项目 开始开发项目
2. 直接lone远程仓库开始开发项目

### 1s 01
1. init
- 用于初始化本地项目
```
git init
```
2. add
- 用于添加现有项目的文件添加至本地仓库
```
git add .
```
3. commit
- 添加暂存版本(复制一个备份)
```
git commit -m "first commit"
```
4. remote add
- remote add 用于添加远程仓库地址到本地
```
git remote add <别名> <远程仓库地址>
```
5. push
- 用于把本地仓库的代码同步到远程仓库
```
git push <别名> <分支>

git push github master

// 也可以使用 -u 绑定到push命令上
git push -u github master
```
6. clone
- 克隆远端项目到本地
```
git clone https://github.com/thenewstnp/Stage-04-07.git
```
7. 忽略文件上传
- 可以在项目根目录后文件夹创建 .gitignore 文件 把需要忽略的文件或文件夹添加进去
