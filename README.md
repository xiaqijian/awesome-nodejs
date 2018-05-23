# awesome-nodejs

这个仓库主要是收集 Node生态 好用的中间件、新闻资讯、网站等，欢迎star😄

目录
--
- [官网](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E5%AE%98%E7%BD%91)
  - nodejs
  - express
  - koa
  - thinkjs
  - eggjs
- [中间件](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E4%B8%AD%E9%97%B4%E4%BB%B6)
  - express
  - koa 前往koa中间件集 👉[awesome-koa](https://github.com/xiaqijian/awesome-nodejs/blob/master/awesome-koa.md)
  
- 框架
  - [express]()
  - [koa]()
- [脚手架工具](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E8%84%9A%E6%89%8B%E6%9E%B6%E5%B7%A5%E5%85%B7)
  - express
  - koa
- [文档](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E6%96%87%E6%A1%A3)
  - nodejs
- [教程](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E6%95%99%E7%A8%8B)
  - express
  - koa
- [面试](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E9%9D%A2%E8%AF%95)
  - nodejs


官网
--
- 英文
  - [Nodejs]()
  - [Express]()
  - [Koa](https://koajs.com/)
  
- 中文
  - [NodeJS](http://nodejs.cn/)
  - [Express](http://expressjs.com/zh-cn/)
  - [Koa](https://koa.bootcss.com/)
  - [ThinkjS](https://thinkjs.org/) 基于 Koa 2.x 实现
  - [Eggjs](https://eggjs.org/zh-cn/intro/) 基于 Koa 开发




[👆🏻返回顶部](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E7%9B%AE%E5%BD%95)

中间件
--
- 请求连接库
  - [request](https://github.com/request/request) 简化版的第三方类http模块，同时支持https 和重定向
  - [superagent](https://www.npmjs.com/package/superagent) 强大并且可读性很好的轻量级ajax API，是适用于nodejs环境的一个关于HTTP方面的库。
- 设置环境变量
  - cross-env
- 类似jQuery库
   - cherrio
- 数据库
   - mysql
   - node-mysql (这个比较好点，有连接池)
   - mongodb
   - mongoose （这个比较好点😄）
   - mongolass [😀教程](https://github.com/mongolass/mongolass)
- 处理cookie，session
   - cookie-parser ( 😃这个用户解析从客户端，传到服务器的cookie 😓这里要注意是cookie-parse`r`)
   - cookie-session
   - express-session
- 处理表单
  - [body-parser](https://github.com/expressjs/body-parser) 转换body内容的中间件，用于处理 JSON, Raw, Text 和 URL 编码的数据。
- 文件上传
   - [multer](https://github.com/expressjs/multer/blob/master/doc/README-zh-cn.md)(🤓这个比较好用)
      -  [nodejs + multer 实现文件上传与下载](https://blog.csdn.net/maci_yera/article/details/71513238?utm_source=itdadao&utm_medium=referral)
      - [使用multer搭建一个图片接收服务器](https://blog.csdn.net/feng020a/article/details/60876970)
    - [formidable](https://github.com/felixge/node-formidable)
    - [express-formidable](https://github.com/utatti/express-formidable#express-formidable-)(在express可以用这个)
   - [multer和formidable区别](https://github.com/xiaqijian/write/issues/20)
- 日志管理
   - morgan （😀morgan是express默认的日志中间件） 
   - log4js-node
   - winston
   - bunyan
- 加密处理
  - crypto （其实就是里面md5加密🤓）[关于nodejs中密码加密的处理](https://blog.csdn.net/kuangshp128/article/details/75162973)
  - bcrypt (bcrypt算法相对来说是运算比较慢的算法，在密码学界有句常话：越慢的算法越安全)[nodejs中使用bcrypt加密](https://blog.csdn.net/original_heart/article/details/78538908?reload)
- 高并发控制
  - eventproxy 使用 eventproxy 控制并发
- 流程控制
  - [async](https://github.com/caolan/async) async是一个流程控制工具包
- 编码问题
  - iconv-lite [使用iconv-lite解决node当中不支持GBK编码的问题](https://segmentfault.com/a/1190000011351573)

[👆🏻返回顶部](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E7%9B%AE%E5%BD%95)


脚手架工具
--
- express
  - [generator-express](https://github.com/petecoop/generator-express)  命令行工具Yeoman 生成 Express 应用程序
  - [express-generator](https://github.com/expressjs/generator)  命令行工具 Express 应用程序生成器
- koa
  - [koa-generator](https://github.com/17koa/koa-generator) koa应用程序生成器

[👆🏻返回顶部](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E7%9B%AE%E5%BD%95)


文档
--
- nodejs
  - [NodeJS中文文档](https://legacy.gitbook.com/book/0532/nodejs/details)

[👆🏻返回顶部](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E7%9B%AE%E5%BD%95)

教程
--
- nodejs
  - [《Node.js 包教不包会》](https://github.com/alsotang/node-lessons)
  - [七天学会NodeJS](http://nqdeng.github.io/7-days-nodejs/)
- express
  - [一起学 Node.js](https://github.com/nswbmw/N-blog) 利用express搭建多人博客

[👆🏻返回顶部](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E7%9B%AE%E5%BD%95)

案例
--
- 爬虫
  - [简书nodejs爬虫系统 ](https://github.com/jiayisheji/blog/issues/7)
  - [nodejs爬虫——汽车之家所有车型数据](http://www.cnblogs.com/woodk/p/6431645.html)

面试
--
- nodejs
  - [如何通过饿了么nodejs面试](https://github.com/ElemeFE/node-interview)  关于解答👉[如何通过饿了么 Node.js 面试(解答)](https://github.com/xiaomuzhu/ElemeFE-node-interview)
  

[👆🏻返回顶部](https://github.com/xiaqijian/awesome-nodejs/blob/master/README.md#%E7%9B%AE%E5%BD%95)







