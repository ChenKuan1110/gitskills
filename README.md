# git 基本知识
---
1.基本配置
```
	git config --global user.name "your_name"
	git config --global user.email "your_email"
```
2.初始化本地仓库
```
	git init
```
3.添加文件到暂存区
```	
	git add file_name
	# 或者
	git add -A # 当前目录下的文档全部被加载到缓存区
```
4.检查状态
```
	git status
```
5.本地提交
```
	git commit -m "commit infomations"
```
	提交信息格式：
		# 提交分支
		# 信息
		# why
6.检查本地修改
```
	git diff
```
7.查看提交信息
```
	git log
```
8.推送到远程仓库(**push**)
```
	git push origin master
```
9.克隆(**clone**)
```
	git clone _url_ #  _url_: 远程仓库地址
```
10.修改上传仓库地址
```
	git remote add origin git@github.com:<your_name>/<your_Repo>.git
```


