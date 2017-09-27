# DevOps Homework

### step1(Done)

使用Vagrant + Ansible搭建一个CI环境，需要安装Jenkins。

**要求：**

+ 最终脚本一定是可运行无报错的(Done)
+ 尽可能少的命令行操作(Done)
+ 尽可能多的使用Ansible模块(Done)
+ 理解每行配置文件的意思(Almost Done)

**扩展思考**

+ 如何在重启虚拟机后Jenkins也自动运行(Done)
+ Jenkins插件如何自动化安装(Done)

### step2

配置一个pipeline, 能实现简单的CD。

**要求：**

+ 本地修改代码(一个简单的html页面即可)，然后提交到github仓库，自动触发pipeline
+ 使用nginx
+ 打开浏览器，可以看到页面变化

**扩展思考**

+ 如何部署到远端机器
+ 如何部署到多台机器
+ 如何使用Nginx做Load balance

### step3

增加数据库，前后端分离。

**要求：**

+ 使用Ansible构建一个MYSQL数据库，需要有一些简单的数据
+ 构建一个或者网上找一个JAVA项目，内容不限，只提供API，可以通过（测试）、编译、打包过程，能够连接到数据库
+ 构建一个或者网上找一个前端项目，内容不限，需要可以连通JAVA API，能够构建运行之后在浏览器页面上展示出数据库的数据
+ 使用Jenkinsfile完善Pipeline过程

**扩展思考**

+ 这种架构如何实现高可用
+ 一个标准的Pipeline是什么样的