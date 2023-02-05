# Repository2
项目描述
项目无法启动的问题解决方案:node19 版本过高,需要降低版本,我降到了17.9.1
相关链接
https://blog.csdn.net/weixin_44582077/article/details/110237056

再按照 之前的
npm install --registry=https://registry.npm.taobao.org
npm run dev ("dev": "SET NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service serve", //pakege-json的scripts里加上前缀启动项目)
