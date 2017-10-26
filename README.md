# commit-change-log
change log message manager

#change log

### 安装

 1. 全局安装
	Commitizen是一个撰写合格 Commit message 的工具。
	
	安装命令如下。

	$ npm install -g commitizen

2. 生成change log 文件

	npm install -g conventional-changelog-cli

	conventional-changelog -p angular -i CHANGELOG.md -s -r 0

	整合webpack 

	{
	  "scripts": {
	    "changelog": "conventional-changelog -p angular -i CHANGELOG.md -w -r 0"
	  }
	}
	
	npm run changelog

3. git cz