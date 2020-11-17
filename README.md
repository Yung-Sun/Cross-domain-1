# 使用方法

## 安装 node-dev
yarn global add node-dev

## 下载代码
https://github.com/Yung-Sun/Cross-domain-1.git

## 进入 qq-com 运行 server.js
cd Cross-domain-1/qq-com; 
node-dev server.js 8888

## 进入 hacker-com 运行 server.js
cd ../hacker-com; 
node-dev server.js 9999

## 设置 hosts
 127.0.0.1 qq.com
 127.0.0.1 hacker.com
 
## 温馨提示
打开两个页面 qq.com:8888/index.html 和 hacker.com:9999/index.html
记得做完之后，删掉 hosts 里的两行，否则 qq.com 无法正常访问！
