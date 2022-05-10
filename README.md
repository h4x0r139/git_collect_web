# 	git_collect_web

[toc]

个人收集的web项目，使用git submodule方式，引用已有项目。


# 环境与使用

submodule的使用、git拉取常见问题 参考：[使用submodle及相关问题.md](https://github.com/h4x0r139/git_collect_note/blob/master/doc/%E4%BD%BF%E7%94%A8submodle%E5%8F%8A%E7%9B%B8%E5%85%B3%E9%97%AE%E9%A2%98.md)



# 项目列表

```
git submodule add git@github.com:macrozheng/mall-learning.git
git submodule add git@github.com:macrozheng/mall.git
git submodule add git@github.com:go-eagle/eagle.git fast_web/eagle
git submodule add git@github.com:Yin-Hongwei/music-website.git music_website
```



## [Mall](https://github.com/macrozheng/mall)

学习教程：http://www.macrozheng.com/#/README

### 项目地址

- mall学习教程：https://github.com/macrozheng/mall-learning
- 后台项目：https://github.com/macrozheng/mall
- 前端项目：https://github.com/macrozheng/mall-admin-web
- 微服务项目：https://github.com/macrozheng/mall-swarm


## [music-website](https://github.com/Yin-Hongwei/music-website)
- starred：2.6k；

Vue + SpringBoot + MyBatis 音乐网站

**技术栈**
- 后端：SpringBoot + MyBatis
- 前端：Vue3.0 + TypeScript + Vue-Router + Vuex + Axios + ElementPlus + Echarts


**开发环境**
- JDK： jdk-8u141
- mysql：mysql-5.7.21-1-macos10.13-x86_64（或者更高版本）
- node：v14.17.3
- IDE：IntelliJ IDEA 2018、VSCode

## [eagle](https://github.com/go-eagle/eagle)
- starred：1.1k；

一款小巧的基于Go构建的开发框架，可以快速构建API服务或者Web网站进行业务开发，遵循SOLID设计原则