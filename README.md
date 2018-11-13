# JavaScript 设计模式

## 面向对象

### 开发环境
- 初始化 npm 环境
  - node v6以上
  - npm init
- 安装 webpack
  - npm i webpack webpack-cli -D
- 安装 webpack-dev-server
  - npm i webpack-dev-server html-webpack-plugin -D
- 安装 babel
  - npm i babel-core babel-loader@7.1.4 babel-polyfill babel-preset-es2015 babel-preset-latest -D

### 什么是面向对象
- 概念
  - 类
  - 对象(实例)
- 三要素：继承 封装 多态
  - 继承，子类继承父类
    - 继承可将公共方法抽离出来，提高复用，减少冗余。
  - 封装，数据的权限和保密。public 完全开放、protected 对子类开放、private 对自己开放。
    - 减少耦合，不该外露的不外露
    - 利于数据、接口的权限管理
    - es6 目前不持支，一般认为 _ 开头的属性是 private
  - 多态，同一接口不同实现。js 应用极少。需要结合 java 等语言的接口、重写、重载等功能。
    - 保持子类的开放性和灵活性
    - 面向接口编程
    - js 引用极少，了解即可
- JS 应用举例
- 面向对象的意义
  - 程序执行：顺序、判断、循环 —— 结构化（goto 语句会导致程序结构的混乱不够结构化所以被淘汰）
  - 面向对象 —— 数据结构化
  - 对于计算机，结构化的才是最简单的
  - 编程应该 简单&抽象

 ### UML 类图
 - Unified Modeling Language 统一建模语言
 - 类图，UML 包含很多种图，和本课程相关的是类图
 - 关系，主要讲解泛化和关联

 #### 画图工具
 - MS Office visio
 - https://www.processon.com/

 #### 关系
 - 泛化，表示继承
 - 关联，表示引用