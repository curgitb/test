# Git使用方法

### 如何推送文件至远程

1. 建立本地仓库

2. 与远程建立连接，测试：

	```
	ssh -T git@github.com
	```

3. init 命令初始化仓库

	```
	git init
	```

4. 手动拷贝文件，并执行add命令

	```
	git add 文件夹1/ 文件夹2/ 文件夹3/
	```

5. commit 命令

	```
	git commit -m "注释"
	```

6. push命令

	```
	git push -u origin main
	```

	