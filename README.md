# 引言
本站点由经管学院实验实训中心维护，并带领梦云智软件开发团队提供技术支持。站点将根据任教教师、学生以及学院领导反馈的意见进行调整甚至临时关闭。任课教师可以直接至825反馈本站点存在的问题。学生可以在Issues中提交自己的问题以及对本站点的相关意见。我们尊重大家每一次反馈，并将在实训中心内部通过认证的方式来决定是否采纳。

## 贡献代码
如果你热爱计算机科学并愿意尝试挑战新的技术，我们更愿意看到你使用`pull request`的方式来贡献代码。

## 在本地启动项目
你还可以将代码`clone`或是直接下载到本地。下载到本地后，你将得到如下目录：
```
└── tuteLib
    ├── app
    │   ├── apple-touch-icon.png
    │   ├── favicon.ico
    │   ├── index.html
    │   ├── robots.txt
    │   ├── scripts
    │   │   └── main.js
    │   └── styles
    │       └── main.css
    ├── bower.json
    ├── gulpfile.js
    ├── package.json
    └── test
        ├── index.html
        └── spec
            └── test.js

6 directories, 11 files
```
本项目采用`yeoman`搭建，项目源码下载完毕后，你需要安装软件`nodejs`。
<br>
`nodejs`安装后，你需要使用命令行软件切换到项目目录，并执行以下命令:
<br>
`npm install --global yo gulp-cli bower` <br>
此时，便可以使用以下命令来查看项目了：<br>

* 执行 `gulp serve` 阅览项目，并在源代码发生变化后，自动刷新页面。
* 执行 `bower install --save <package>` 安装前端的依赖包(package替换为包名)
* 执行 `gulp serve:test` 在浏览器中启动测试
* 执行 `gulp` 创建生产环境下使用的项目。
* 执行 `gulp serve:dist` 阅览创建的生产环境下的项目。

<hr>
GOOD LUCK！
