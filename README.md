# wanxin-p2p-manager

## 项目地址

| Github地址                                         | 说明            |
| -------------------------------------------------- | --------------- |
| https://github.com/mikuhuyo/wanxin-p2p-web.git     | 前端工程        |
| https://github.com/mikuhuyo/wanxin-p2p.git         | 后端工程        |
| https://github.com/mikuhuyo/wanxin-p2p-manager.git | 后台前端工程    |
| https://github.com/mikuhuyo/tencent-sms.git        | Tencent短信服务 |
| https://github.com/mikuhuyo/minio.git              | 存储服务        |

## 项目目录

```shell
├── build                      # 构建相关 
├── mock                       # 项目mock 模拟数据
├── plop-templates             # 基本模板
├── public                     # 静态资源
│   │── favicon.ico            # favicon图标
│   └── index.html             # html模板
├── src                        # 源代码
│   ├── api                    # 所有请求
│   ├── assets                 # 主题 字体等静态资源
│   ├── components             # 全局公用组件
│   ├── directive              # 全局指令
│   ├── filters                # 全局 filter
│   ├── icons                  # 项目所有 svg icons
│   ├── lang                   # 国际化 language
│   ├── layout                 # 全局 layout
│   ├── router                 # 路由
│   ├── store                  # 全局 store管理
│   ├── styles                 # 全局样式
│   ├── utils                  # 全局公用方法
│   ├── vendor                 # 公用vendor
│   ├── views                  # views 所有页面
│   ├── App.vue                # 入口页面
│   ├── main.js                # 入口文件 加载组件 初始化等
│   └── permission.js          # 权限管理
├── tests                      # 测试
├── .env.xxx                   # 环境变量配置
├── .eslintrc.js               # eslint 配置项
├── .babelrc                   # babel-loader 配置
├── .travis.yml                # 自动化CI配置
├── vue.config.js              # vue-cli 配置
├── postcss.config.js          # postcss 配置
└── package.json               # package.json

```

## 项目运行

```shell
# clone the project
git clone https://github.com/YueLiMin-say/wanxin-p2p-manager.git

# install dependency
npm install

# develop
npm run dev

# build for test environment
npm run build:stage

# build for production environment
npm run build:prod
```

## 启动错误

无法获取`node-sass`: `npm install node-sass@4.9.0 --save`或者`cnpm install node-sass@4.9.0 --save`

如果是MacBook上面的指令就不适用了, 得用`sudo npm install node-sass --unsafe-perm --save-dev`.
