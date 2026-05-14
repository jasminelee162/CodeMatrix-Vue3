# CodeMatrix Vue 3 前端

后端仓库：https://github.com/jasminelee162/CodeMatrix-Backend

这是一个基于 Vue 3 和 Vite 的前端应用，用于展示软件度量与分析结果。前端页面以多个模块展示度量信息，配合后端服务完成数据计算和结果展示。

## 项目简介

- 页面采用 Vue Router 切换，支持不同度量模块展示
- 使用 Axios 与后端 API 通信获取分析数据
- 使用 ECharts 等图表展示度量结果

## 模块说明

### 5.1 功能点度量

此模块展示功能点度量结果，支持输入和分析功能点数据。

<img width="2559" height="1233" alt="image" src="https://github.com/user-attachments/assets/e6a81e55-19a7-4ff5-b628-f4fb0bd52bed" />

### 5.2 用例点度量

此模块展示用例点度量结果，可用于评估需求用例的规模和复杂度。

<img width="2535" height="1403" alt="image (1)" src="https://github.com/user-attachments/assets/c2453601-ffea-4a83-9334-e6b055abab4b" />


### 5.3 面向对象度量

此模块展示面向对象度量（如 CK 度量），用于分析类图和对象设计质量。

<img width="2559" height="1236" alt="image (2)" src="https://github.com/user-attachments/assets/b4429f0b-ec03-4eac-81a4-6e371e71c00c" />


### 5.4 代码行度量

此模块展示代码行度量结果，并对项目代码规模进行统计和分析。

<img width="2527" height="1403" alt="image (3)" src="https://github.com/user-attachments/assets/765c8433-e6ff-4287-8dfe-dfc737097090" />


### AI解析与优化

此模块用于 AI 解析和优化建议展示，可辅助分析代码质量并给出改进方向。

<img width="2559" height="1237" alt="image (4)" src="https://github.com/user-attachments/assets/19bb088e-d7a6-4b5b-9fcc-d508c248c671" />


## 启动方式

```bash
npm install
npm run dev
```

打开浏览器访问 `http://localhost:5173`。

## 说明

前端依赖后端服务完成度量计算与数据结果展示，建议同时启动后端仓库以获得完整功能体验。
