# React Debug

<p align="center">
  简体中文
  | 
  <a href="/README_en.md">English</a>
</p>

## 快速启动

### 安装依赖
```shell
cd react && yarn
cd react-app && yarn
```

### 修改路径
1. 编辑器打开 `/react-app/public/react.development.js.map`、`/react-app/public/react-dom.development.js.map`
2. 查找 "../../../../packages" 全部替换为"绝对路径"（如 /Users/h/react-debug/react/packages）

### 启动项目
```shell
yarn start
```

### 启动调试
启动 VS Code，打开"运行和调试"面板，点击"React Debug"，启动调试。

## 说明
调试的 react 版本为 18.1.0

react-app/public 目录下的`react.development.js`、`react.development.js.map`、`react-dom.development.js` 和 `react-dom.development.js.map` 是通过运行 `cd react && yarn build`，然后在 `react/node_modules/react/umd`、`react/node_modules/react-dom/umd` 目录下可找到。

想了解调试环境的自主搭建的请看 [gitCommit](https://github.com/xingleibinghun/react-debug/commit/5af4f7cbbe9517d127922d5605a2111543b9209d) 或 [参考文章](https://mp.weixin.qq.com/s/Yfmb11mmvfXg2FlEu7UlXA) 。
