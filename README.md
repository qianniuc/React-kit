# React-kit
React开发脚手架

### 技术栈

1. React
2. Mobx
3. ES6

### 项目运行
```
# 运行dev环境
npm run dev

# 运行debug环境
npm run debug

# 测试环境打包
npm run test

# 开发环境打包
npm run build
```

### 目录结构
```
React-kit
├── .babelrc                    // babel的配置文件
├── .eslintrc                   // eslint语法检查配置文件
├── .gitignore                  // git忽略文件和文件夹配置
├── dist                        // build结果目录
├── package.json                // 依赖配置文件
├── README.md
├─┬ src                         // 源码目录
│ ├── components                // 展示组件
│ ├── containers                // 容器组件
│ ├── images
│ ├── json                      // 模拟数据接口
│ ├── mobx
│ ├── routes
│ ├── services
│ ├── static                    // 静态资源，如favicon.ico,robots.txt等
│ ├── utils
│ ├── views                     // 视图模板 
│ ├── env.js                    // 环境配置
│ └── index.js                  // 入口文件
└── webpack.config.js           // webpack配置文件
   
```
