## 简介（Introduction)

webpack提取css原理验证demo

## 技术栈（Scheme）

webpack5 + mini-css-extract-plugin

## 项目设计结构

```js
.
├── LICENSE
├── README.md
├── config
│   └── webpack.config.js
├── dist
│   ├── css
│   │   └── app.7c964d39ee6900c791ab.css
│   └── js
│       └── app.ba46ec2a8bcc449864ec.js
├── global.d.ts
├── package.json
├── pnpm-lock.yaml
└── src
    ├── app.css
    ├── async.css
    ├── async.js
    ├── bar.css
    ├── foo.js
    └── index.js
```

## 使用（Usage）

### 克隆仓库
 
git clone git@github.com:willson-wang/webpack-css-extract-demo.git
 
### 安装依赖
 
pnpm install
 
### 构建模式

正常构建
```
pnpm build
```

