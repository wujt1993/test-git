#### 一、创建版本库
- 初始化版本库
	- git init
- 添加文件
	- git add 文档.md
- 提交添加的文件
	- git commit -m '添加git文档'

#### 二、时光穿梭机
- git status: 查看结果
- git diff: 查看修改的内容
- git status：查看当前git状态

##### 1、版本回退
- git log：查看提交历史
- git reset --hard HEAD^ : 会退到上个版本
- git reset --hard HEAD^^ : 会退到上两个版本
- git reset --hard HEAD~100 : 会退到上一百个版本
- git reset --hard id: 回退到id版本

##### 2、撤销修改
- git checkout -- README.md
	- 暂缓区有内容则恢复到暂缓区的状态
	- 暂缓区没内容则恢复到版本库状态
	- 恢复误删的文件


#### 3、删除文件
- git rm test.txt
	-删除文件