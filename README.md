
## 代码结构
```
├── build                      // 构建相关  
├── config                     // 配置相关
├── node_module                // npm加载所需的项目依赖模块
├── src                        // 源代码
│   ├── api                    // 所有请求
│   ├── assets                 // 主题 字体 图片等静态资源
│   ├── common                 // 全局公用配置
│   │   ├── config             // 配置全局路由权限和错误捕获
│   │   ├── mixin              // 一些vue公用的mixin
│   │   ├── js                 // 编写公有的方法
│   │   └── style              // 编写公有的样式
│   ├── components             // 全局公用组件
│   ├── router                 // 路由
│   ├── store                  // 全局 store管理
│   ├── views                  // view
│   ├── App.vue                // 入口页面
│   └── main.js                // 入口 加载组件 初始化等
├── static                     // 第三方不打包资源
├── .babelrc                   // babel-loader 配置
├── eslintrc.js                // eslint 配置项
├── .gitignore                 // git 忽略项
├── index.html                 // html模板
└── package.json               // package.json
```


## 功能相关介绍
|模块|功能|页面编码|描述|
|:---|:--|:------|:---|
|登录|登录|login|菜单中不显示|
|401|401|401|角色无访问权限时进入这个页面|
|404|404|404|访问菜单不存在时进入这个页面|
|首页|首页|home||
|运维中心||B04||
|-|问答管理|B0401||
|-|专栏管理|B0402||
|-|文章管理|B0403||
|-|讲堂管理|B0404||
|-|活动管理|B0405||
|文件库||B03||
|-|图片管理|B0301||
|-|文件管理|B0302||
|论坛配置||B02||
|-|首页轮播|B0201||
|-|技术频道|B0202||
|-|提示语|B0203||
|-|广告位|B0204||
|-|讲座推荐|B0205||
|-|活动推荐|B0206||
|-|标签类型管理|B0207||
|-|标签管理|B0208||
|系统管理||B01||
|-|用户管理|B0101||
|-|角色管理|B0102||
|-|菜单管理|B0103||
|-|区域管理|B0104||
|-|字典管理|B0105||
|-|系统日志|B0106||

## 基本业务分析