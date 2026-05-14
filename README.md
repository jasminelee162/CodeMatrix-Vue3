# CodeMatrix Vue 3 前端

后端仓库：https://github.com/jasminelee162/CodeMatrix-Backend

这是一个基于 Vue 3 和 Vite 的前端应用，负责展示软件度量与分析结果。

## 主要功能

- 主页概览
- 功能点度量
- 用例点度量
- 面向对象度量（CK 度量）
- 代码度量
- 可与后端服务对接，显示分析结果和图表

## 技术栈

- Vue 3
- Vite
- Vue Router
- Axios
- ECharts

## 启动方式

```bash
npm install
npm run dev
```

打开浏览器访问 `http://localhost:5173`，即可进入前端页面。

## 目录结构

- `src/components`：页面组件和侧边导航
- `src/main.js`：路由配置与 Vue 应用挂载

本项目前端依赖后端服务完成度量计算与数据结果展示，建议同时启动后端仓库来完成整体体验。
