# weapp-plugin-require


分析 js 文件的 npm 依赖，进行拷贝

```
1. 修复window环境编译出错
2. 新增支持配置alias功能
```
## 安装 

```bash
npm i weapp-plugin-require -D
```

## 使用
weapp.config.js

```js
module.exports = {
  plugins: [
    ['weapp-plugin-require', {
        ignore: undefined,
        match: /\.js$/,
        ...config
    }]，
    // 'weapp-plugin-require',
  ],
};
```