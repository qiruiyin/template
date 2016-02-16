# 网站快速开发模板

## 开发环境
以nodejs为基础，gulp搭建前端自动化模块，并采用bower进行包模块管理

* 'npm install -g gulp'
* 'bower install -g bower'

### gulpfile 主要模块

* gulp start 启动项目
		browser-sync 启动服务器
		watch 监听修改
		sass scss翻译
		html 静态模板渲染
* gulp test js和css检查
		jshint js校验
		css-lint css校验
* gulp 生成压缩包
		image 图片压缩
		dist js和css压缩及生成压缩包

##项目运行
* 'npm install'
* 'gulp start'
