```
├── Readme.md                   // 使用帮助
├── package.json                // 应用依赖源
├── mainifest.json              // HB打包发布配置文件
├── config                      // 环境配置
├── dist                        // 发布文件
│   ├── fonts                   // 字体文件，供hb原生代码调用
│   ├── pages                   // html5商城代码，需要修改为vue
|   ├── static                  // 编译发布的静态文件
│   │   └── css                 // 编译后的样式文件
│   │   └── fonts               // 字体文件
│   │   └── img                 // 图片
│   │   └── js                  // 编译后的JS文件
│   │   └── *.html              // 各模块的入口页面
├── src                         // 源码目录
│   ├── api                     // Api定义目录
│   │   └──                     //
│   └── common                  // 通用静态文件目录
│   │   └── css                 // css
│   │   └── emotion             // 表情
│   │   └── fonts               // 字体
│   │   └── icon                // 图标
│   │   └── img                 // 图片
│   │   └── js                  // 通用JS源码
│   │   │   └── app             // 通用JS源码
│   │   │   └── mui             // MUI源码
│   ├── components              // 组件目录
│   ├── modules                 // 模块目录
│   ├── routers                 // 模块路由定义目录
│   ├── stores                  // 状态管理定义目录
├── node_modules                // 依赖文件
├── templates                   // 模块html模板
├── docs                        // 文档目录
├── build                       // 配置
│   ├── build.js                // 构建文件
│   ├── check-version.js        //
│   ├── dev-client.js           //
│   ├── dev-server.js           //
│   ├── postcss.config.js       //
│   ├── utils.js                //
│   ├── vue-loader.conf.js      //
│   ├── build.js                // 构建文件
│   ├── webpack.base.conf.js    // 通用配置
│   ├── webpack.config.dev.js   // 组件开发配置
│   ├── webpack.config.prod.js  // 组件发布配置
│   └── release.sh              // 执行文件
└── .babelrc                    // babel配置
```
