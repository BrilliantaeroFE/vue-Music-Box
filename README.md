# vue-Music-Box

![image](https://img.shields.io/badge/vue-2.5.13-blue.svg)
![image](https://img.shields.io/badge/vue--router-3.0.1-blue.svg)
![image](https://img.shields.io/badge/vuex-3.0.1-blue.svg)
![image](https://img.shields.io/badge/mint--ui-2.2.13-blue.svg)

## 简介

`vue-Music-Box` 是一个音乐播放器,吸取网易云音乐，QQ音乐等主流播放器的优点，它基于 [vue.js](https://github.com/vuejs/vue) 和 [mint-ui](https://github.com/ElemeFE/mint-ui)。使用了目前主流的前端技术栈。

##### vue-Music-Box 是一个完备的音乐播放器,支持歌手写真,歌词显示,进度条等。

##### 注意：该项目使用 mint-ui@2.2.13+ 版本，所以最低兼容 vue@2.5.0+

## 前序准备
你的本地环境需要安装 [node](http://nodejs.cn/) 和 [git](https://git-scm.com/)，本项目技术栈基于 [ES2015+](http://es6.ruanyifeng.com/)、[vue](https://cn.vuejs.org)、[vue-router](https://router.vuejs.org/zh-cn/)、[vuex](https://vuex.vuejs.org/zh-cn/) 和 [mint-ui](https://github.com/ElemeFE/mint-ui)，所有的音乐资源均来自豆瓣音乐接口，提前了解和学习这些知识会对使用本项目有很大的帮助。

如果你是Vue初学者，这里有一些资源可以帮助到你

- [新手向 Vue 2.0 的建议学习顺序](https://zhuanlan.zhihu.com/p/23134551?refer=evanyou)
- [ES6入门 阮一峰](http://es6.ruanyifeng.com/)
- [webpack构建优化](https://zhuanlan.zhihu.com/p/26710831) （webpack < 4）

## 说明
> 如果对你有帮助，你可以点右上角 "star"支持一下，非常感谢！🌹

> 或者你可以 "follow（关注）" 一下作者，我正在不断开源更多实用的项目。

> 如有问题可以直接在 Issues 中反馈

## 开发
```bash
# 克隆项目
git@github.com:BrilliantaeroFE/vue-Music-Box.git

# 安装依赖
npm install / yarn add

# 建议不要用cnpm安装，某些依赖可能无法安装， 可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务：localhost:8020
npm run dev / yarn start
```
## 发布

```
# 构建生产环境
npm run build
```
