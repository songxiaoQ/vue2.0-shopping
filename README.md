### 慕课网 - Vue+Webpack打造todo应用 - 课程源码（程序可正常运行）

#### 前言
此源码基于 [慕课网](https://www.imooc.com/) Jokcy老师的 [Vue+Webpack打造todo应用](https://www.imooc.com/learn/935) 视频教程编写，所用到的模块包均为当前最新版本，源码编写完成日期：2018年3月13日。  

#### 使用须知
- **使用&参考此源码，需要您对HTML、CSS、JavaScript、Node.js、npm等有一定的了解和实践。**  

#### 使用步骤

##### 安装依赖
- 安装npm依赖：`npm install`


##### 开发环境
- 启动项目：`npm run dev`
- 浏览器预览：localhost:8000


##### 生产环境
- 启动项目打包：`npm run build`

### window 7 系统会遇到的问题

看视频跟着敲代码时window7系统可能会遇到以下问题：

> 1、问题：`ReferenceError: _dirname is not defined`

&emsp;办法：__dirname：前面是两个下划线

> 2、问题：使用 `hot // 不刷新热加载数据`时，页面的样式会出现多次

&emsp;办法：pack.josn中这样配置

`"dev": "cross-env NODE_ENV=development webpack-dev-server --mode development --config webpack.config.js"`

> 3、出现这个错误提示：<br/>
>`Error: webpack.optimize.CommonsChunkPlugin has been removed, please use config.optimization.splitChunks instead.
`

&emsp;办法：代码中有具体实现


**未完待续。。。**
