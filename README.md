# Repository2
项目描述
项目无法启动的问题解决方案:node19 版本过高,需要降低版本,我降到了17.9.1
相关链接
https://blog.csdn.net/weixin_44582077/article/details/110237056

再按照 之前的
npm install --registry=https://registry.npm.taobao.org
npm run dev ("dev": "SET NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service serve", //pakege-json的scripts里加上前缀启动项目)

切换中文的方式
1.克隆项目
2.切换i18n分支
3.删除 tui等一些文件 https://blog.csdn.net/m0_48895571/article/details/124126057#:~:text=1%E3%80%81vue-element-adminpackage.json%20%E5%88%A0%E9%99%A4%E2%80%98tui-editor%E2%80%99%EF%BC%9A%E2%80%981.3.3%E2%80%99%E4%BE%9D%E8%B5%96%E9%A1%B9%E3%80%82%202%E3%80%81vue-element-adminsrccomponents,%E5%88%A0%E9%99%A4MarkdownEditor%E6%96%87%E4%BB%B6%E5%A4%B9%E3%80%82%203%E3%80%81vue-element-adminsrcviewcomponents-demo%20%E5%88%A0%E9%99%A4markdown.vue%E6%96%87%E4%BB%B6%E3%80%82


4.执行命令
npm install --registry=https://registry.npm.taobao.org
npm run dev ("dev": "SET NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service serve", //pakege-json的scripts里加上前缀启动项目)
