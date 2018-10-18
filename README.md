# vueProjectTest
vue+iview项目实践

# 登陆
* git访问地址
（https://wyn5111.github.io/vueProjectTest/）
* 用户名与密码
用户名：123 密码：123

# 项目构建
高效、协同、模块化开发的要求大势所趋，快速构建高性能项目的目标迫在眉睫。Webpack 作为一个现代 JavaScript 应用程序的静态模块打包器，是构建web项目的首选工具。
1. webpack简介
>>webpack 处理应用程序时，它会递归地构建一个依赖关系图(dependency graph)，其中包含应用程序需要的每个模块，然后将所有这些模块打包成一个或多个 bundle。其包含四个核心概念:入口，出口，loader，插件，更多内容可查看（https://www.webpackjs.com/concepts/）
2. Webpack构建Vue项目
webpack构建vue项目需安装node环境，安装包管理工具npm，安装vue脚手架
```
  npm install vue-cli -g
```
构建项目，在工作目录下，执行命令
```
vue init webpack 项目名字
```
构建成功之后，转到项目目录，安装项目依赖，执行命令
```
npm install
```
安装vue路由模块vue-router和网络请求模块，执行命令
```
npm install vue-router vue-resource -save
```
启动项目，执行命令
```
npm run dev
```

