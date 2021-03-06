---
title: 记一次使用vue开发的流程
date: 2018-04-27 22:34:59
categories: node.js
tags:
  - node.js
---
#### 开发前准备
1. 项目开发规约的制定（参考腾讯前端团队规约http://alloyteam.github.io/CodeGuide/#naming）
2. git管理方式
3. 使用easymock搭建API服务
4. 官方文档学习
5. github搜索资源
6. 页面功能组件划分
7. 确定开发工具的版本

#### 脚手架构建
1. vue-cli构建项目基础结构
2. 项目目录结构划分
3. 移动端UI框架,使用mint-ui
4. 页面路由切换,页面间跳转实现及参数传递
5. axios请求API封装
6. 过渡动画处理
7. vuex使用

#### 打包部署
1. mint-ui按需加载
2. 赖加载修改
3. 打包nginx静态部署

#### 优化及一些坑
1. 数据初始化
2. 路由参数变化，模版不变处理
3. 工具函数的封装及使用