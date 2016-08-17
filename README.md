# 常用前端技术栈

## 核心技术
* html
  * html5 -- 语义化,svg,canvas,localStorage
* css
  * css2 -- 字体图标,sprite
  * css3 -- 动画,flexbox,rem,border-box模型
* ECMAScript
  * es3
  * es5 -- 大量新函数。 getter/setter
  * es2015(es6) -- let,const,class,async,module,set等

## 编程思想
* 编程范式
  * OOP -- 面向对象编程
  * FP -- 面向函数编程
* 架构模式
  * MVC -- 模型(model)－视图(view)－控制器(controller)
  * MVVM -- model-view-viewMode
  * flux -- action-dispatcher-store-view 数据流管理
  * 组件化开发 -- 页面功能组件为单位聚合前端资源
* 其他
  * 设计模式 -- 工厂,单例,适配器,组合等
  * 设计法则 -- 单一职责,里氏替换原则,依赖倒置原则,接口隔离原则,迪米特法则,开闭原则,组合/聚合复用原则
  * 算法 -- 基本用不到。用到了也是一些具体的数据函数或者直接是个库无需具体理解。只有在写游戏和写框架的时候用到一点点。
  * 编程原理 -- 感觉对前端也用处不大

## 工程开发
* 框架
  * jquery -- 解决兼容性,有各种语法糖
  * react,vue,angularjs -- 解决复杂app的可维护性
  * lodash,underscore -- js工具库
  * CSS Modules -- 模块化css解决方案
* 构建工具
  * gulp -- 文件数据流解决方案
  * webpack -- app项目文件打包解决方案
  * FIS3 -- 超级全家桶，前端构建的大部分功能都有
* 编译工具
  * sass,less -- CSS 预处理语言
  * typescript -- js的超集 增加类型检查和显性接口 大大增加了js语言的抽象能力
  * babel -- ES2015转换 支持低版本浏览器ES2015的运行
* 编码规范
  * js -- 多与三层分模块分函数
  * css -- BEM 
  * html -- 语义化
  * 备注 -- jsdoc
* 版本管理
  * git -- 分布式版本控制系统 管理项目文件
  * svn -- 请淘汰
* 自动化测试
  * mocha,jasmin,jest -- 单元测试
  * ui测试 -- 现阶段没有比较好的解决方案，都是一些残次品。c#有个自动化ui测试可以一试。
* 部署 -- cdn,多域名,hash文件名
  

## 扩展技术
* svg -- 画图形
* canvas
  * 动画 -- 用下面的！
  * 游戏 -- 白鹭,layabox,Cocos2d-JS 性能堪忧。收费模式不好。
* node
  * 构建工具 -- gulp fis3 webpack
  * 服务器 -- 性能被秒杀。还要很复杂的情况下才支持双核。网上传的高并发速度快。也只是异步IO导致。其他所有语言都支持异步IO只是默认是同步IO。优点：js程序员多社区活跃。
* 浏览器特性和兼容 -- 达到一定的代码量才能掌握的东西。兼容程度和用户群挂钩。
* pc手机端差异 -- 手机普及html5,ES5,不兼容ES2015。pc ie8占比大 谷歌内核支持ES2015。
* 安全性 -- https, 其他的一些解决方案都是只能提高破解难度或者做一些预警和统计并不能很好的防御
* 性能 -- get强制缓存,请求合并,cdn,多域名,js缓存,合并渲染等
