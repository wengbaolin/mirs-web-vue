## 项目说明

> 电影智能推荐系统([后端地址](https://github.com/firery/mirs))前端的Vue实现。**Demo 网站已过期，接口已不能请求。另外依赖的库相对目前来说太旧，升级会遇到相应的版本兼容问题。故项目已没有太大的参考价值，想要学习 Vue 的朋友请移步官方文档或参考其他较新项目。**

## 构建步骤

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:3000
npm run dev

# build for production with minification
npm run build
```

## 项目结构
```
index.html  
├── main.js                       # 入口地址
├── api                           # 对后台API的封装
│   ├── api.js                    # 抽取出API请求
│   └── ...                       # 不同模块的请求
├── components                    # Vue组件
│   ├── common                    # 通用组件
│   └── ...                       # 其他模块组件
├── filters                       # Vue的自定义过滤函数
├── router                        # 路由
├── store                         # vuex的集中式store
│   ├── index.js                  # 组装模块并导出 store 的地方
│   ├── actions.js                # 根级别的 action
│   ├── mutations.js              # 根级别的 mutation
│   ├── getters.js                # 根级别的 getters
│   └── modules                   # store模块
│       ├── notification.js       # 通知模块
│       └── ...                   # 其他模块
└── utils                         # 项目的一些自定义模块等
└── views                         # View组件
```

## 技术选型

+ 核心框架：[Vue](https://cn.vuejs.org/v2/guide/)
+ 状态管理：[Vuex](https://vuex.vuejs.org/zh-cn/intro.html)
+ 路由映射：[vue-router](https://router.vuejs.org/zh-cn/)
+ UI组件库：[Muse-UI](https://museui.github.io/#/index),[Element](http://element.eleme.io/#/zh-CN/component/quickstart)
+ HTTP请求库：[axios](https://github.com/mzabriskie/axios)
+ CSS的预处理框架: [Stylus](http://stylus-lang.com/),[中文文档](http://www.zhangxinxu.com/jq/stylus/)
+ 资源加载打包工具：[Webpack](https://webpack.github.io/)
+ 代码规范工具：[eslint](http://eslint.org/)
+ 其他：[ES6](https://wohugb.gitbooks.io/ecmascript-6/content/index.html)
