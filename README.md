# generator-loopback-vue 
>当前build,CI状态:
[![Build Status](https://travis-ci.org/qxl1231/generator-loopback-vue.svg?branch=master)](https://travis-ci.org/qxl1231/generator-loopback-vue)
[![CircleCI](https://circleci.com/gh/qxl1231/generator-loopback-vue.svg?style=svg)](https://circleci.com/gh/qxl1231/generator-loopback-vue)




![image](https://cloud.githubusercontent.com/assets/8305742/17387903/810c8b16-5a2a-11e6-862a-9306067bfc34.png)

![image](https://cloud.githubusercontent.com/assets/8305742/17387949/dce5d7d0-5a2a-11e6-9e1d-5fe93b2924b2.png)

The project is generated by [LoopBack](http://loopback.io).+[vue.js](http://vuejs.org).

# 启动:
       1. cnpm i   
       2.npm run watch:js & node .(hot reload)

>遇到问题1:loopback+vue 不能运行
答:1.npm install   2.npm run build:js  3.node .

>问题2:热部署
To use hot reload, please try this command:npm run watch:js & node .

> 启动:$npm run watch:js & node .

 
>问题3:If you have error, try this:

>npm install
  vueify-insert-css vue-hot-reload-api
  babel-core babel-preset-es2015
  babel-plugin-transform-runtime babel-runtime@5
  --save-dev
  
  
# Hot reloading detail: 
https://github.com/vuejs/vueify

# loopback cmd:
 - slc loopback 初始化项目
 - slc loopback:datasource
 - slc loopback:model
 - slc loopback:relation
 - slc loopback boot-script


# others:deploy and status

 - slc deploy http://usr:pwd@localhost:port  
 - slpmctl -C http://usr:pwd@localhost:8701 ls   

 - slpmctl -C http://usr:pwd@domain:8701 status 

 - pm2 start -n weather app.js

 - pm2 start -n app_update_server server.js

# LICENSE

MIT