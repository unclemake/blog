# 常用前端技术栈

## 核心技术
* html
  * html5 -- 语义化,svg,canvas,localStorage
* css
  * css2 -- 字体图标,sprite
  * css3 -- 动画,flexbox,rem,vw,border-box模型
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
  * 算法 -- 平常用的地方不多，大部分算法搜索也能搜索到。只有在写游戏和写框架的时候情况比较复杂需要自己写算法。
  * 编程原理 -- 平常用的地方不多

## 工程开发
* 框架
  * jquery -- 解决兼容性,有各种语法糖
  * react,vue,angularjs -- 解决复杂app的可维护性
  * lodash,underscore -- js工具库
  * CSS Modules -- 模块化css解决方案
* 构建工具
  * gulp -- 文件数据流解决方案
  * webpack -- app项目文件打包解决方案
  * FIS3 -- 前端构建的大部分功能都有
* 编译工具
  * sass,less -- CSS 预处理语言
  * typescript -- js的超集 增加类型检查和显性接口等,大大增加了js语言的抽象能力
  * babel -- ES2015转换ES3
* 编码规范
  * js -- 参考大厂的js规范
  * css -- BEM,声明顺序等
  * html -- 语义化
  * 备注 -- jsdoc
* 版本管理
  * git -- 分布式版本控制系统 管理项目文件
  * svn -- 淘汰中
* 自动化测试
  * mocha,jasmin,jest -- 单元测试
  * ui测试 -- 现阶段没有比较好的解决方案。c#有个自动化ui测试可以一试。
* 部署 -- cdn(http2可不使用),hash文件名强制缓存

## 扩展技术
* svg -- 画图形
* canvas
  * 动画 -- 有很多轻量级的canvas框架
  * 游戏 -- 白鹭,layabox,Cocos2d-JS 3D性能相对桌面都很一般。
* node
  * 构建工具 -- gulp fis3 webpack
  * 服务器 -- 性能被秒杀。异步IO高并发速度快。其他所有语言也都支持异步IO。优点：js程序员多社区活跃（其实我也不信囧）。
* 浏览器特性和兼容 -- 达到一定的代码量才能掌握的东西。兼容程度和用户群挂钩。
* pc手机端差异 -- 手机普及html5,ES5,局部不兼容ES2015。pc ie8占比不高不低,谷歌内核支持ES2015。
* 安全性 -- https, 其他的一些解决方案都是只能提高破解难度或者做一些预警和统计并不能很好的防御
* 性能 -- get强制缓存,请求合并,cdn,js缓存,合并渲染等
