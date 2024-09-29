# 项目名称

uniapp小程序

## 功能特性

uniapp小程序

## 快速开始

开始前 请进行 vscode 配置 用来保存时根据 eslint 整理代码
https://zhuanlan.zhihu.com/p/611951084

ui框架地址
https://www.uvui.cn/
npm i 引入项目依赖

## vscode 插件配置

请下载 esLint，styleLint 插件。
并且在 vscode 的设置中添加
// 根据stylelint和eslint保存自动格式化
"editor.codeActionsOnSave": {
  "source.fixAll.stylelint": "explicit",
  "source.fixAll.eslint": "explicit"
},
"stylelint.validate": ["css", "less", "vue", "scss","sass"],
"stylelint.snippet": [
  "css",
  "less",
  "postcss",
  "scss",
  "sass"
],

### 构建

npm run build:mp-weixin

### 运行

npm run dev:mp-weixin
