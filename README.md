# layuiAdmin后台管理模板学习（单页版）  
请联系qq：929918989

# 关于产品
layuiAdmin pro 是一款由 layui 官方出品的高质量付费产品，可用于快速开发单页面应用的后台管理系统。

单页版预览
https://www.layui.com/admin/pro/
![demo3](https://github.com/weixinbao/layuiAdmin-Learn/blob/master/demo3.png)

单页版文档
https://fly.layui.com/docs/5/
![demo1](https://github.com/weixinbao/layuiAdmin-Learn/blob/master/demo1.png)

使用方法
https://www.layui.com/demo/
![demo2](https://github.com/weixinbao/layuiAdmin-Learn/blob/master/demo2.png)

# 运行说明：
直接运行入口文件即可： start/index.html

# 目录说明：
dist/  经过打包压缩后的文件，一般用于正式环境使用
src/   源代码，一般用于开发环境

# 源码构建
项目可采用 gulp 构建，gulpfile.js 是任务脚本，package.json 是任务配置文件
step1：确保你的电脑已经安装好了 Node.js
step2: 命令行安装 gulp：npm install gulp -g
step3：切换到 layuiAdmin 项目根目录（即 gulpfile.js 所在目录），命令行安装任务所依赖的包：npm install
安装完成后，即可直接执行命令：gulp
即可完成 src 到 dist 目录的构建

# 声明
仅供自己学习研究使用，引起任何法律纠纷概不负责
