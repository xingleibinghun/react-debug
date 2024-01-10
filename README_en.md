# React Debug

<p align="center">
  English
  | 
  <a href="/README.md">简体中文</a>
</p>

## Quick Start

### Install Dependencies
```shell
cd react && yarn
cd react-app && yarn
```

### Modify Paths
1. Open `/react-app/public/react.development.js.map` and `/react-app/public/react-dom.development.js.map` in an editor.
2. Replace all occurrences of "../../../../packages" with the "absolute path" (e.g., /Users/h/react-debug/react/packages).

### Start the Project
```shell
yarn start
```

### Start Debugging
Launch VS Code, open the "Run and Debug" panel, click "React Debug" to start debugging.

## Notes
The debug version of React is 18.1.0.

The files `react.development.js`, `react.development.js.map`, `react-dom.development.js`, and `react-dom.development.js.map` in the react-app/public directory can be found by running `cd react && yarn build`, and then in the `react/node_modules/react/umd` and `react/node_modules/react-dom/umd` directories.

For information on setting up the debug environment manually, refer to [gitCommit](https://github.com/xingleibinghun/react-debug/commit/5af4f7cbbe9517d127922d5605a2111543b9209d) or check [the reference article](https://mp.weixin.qq.com/s/Yfmb11mmvfXg2FlEu7UlXA) .
