# awesome-nodejs

这个仓库主要是收集 Node生态 好用的中间件、新闻资讯、网站等，欢迎star😄

目录
--
- [官网]()
  - nodejs
  - express
  - koa
  - thinkjs
  - 
- 中间件
  - express
  - koa
- 框架
  - [express]()
  - [koa]()

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
  - [ThinkjS](https://thinkjs.org/) 从 3.0 开始，框架底层基于 Koa 2.x 实现，兼容 Koa 的所有功能
  - [Eggjs](https://eggjs.org/zh-cn/intro/)基于 Koa 开发

中间件
--

- 设置环境变量
  - cross-env

- 请求连接库
   - request
   - superagent

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




