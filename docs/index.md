# 图解 React 原理系列

> 基于[`react@16.13.1`](https://github.com/facebook/react/tree/v16.13.1)(尽可能跟随 react 版本的升级, 持续更新). 用大量配图的方式, 致力于将`react`原理表述清楚.

## 使用指南

### 适用读者

1. 对`react`,`react-dom`开发 web 应用有实践经验
2. 期望深入了解`react`内在作用原理

### 主要类容

1. [基本包结构](./01-basic)
2. [启动模式和初始化](./02-bootstrap)
3. [初次渲染 render 流程](./03-render-process)
4. [合成事件机制](./04-syntheticEvent)
5. [调度机制 scheduler](./05-scheduler)
6. [更新机制](./06-update-process)
7. `context`机制
8. 任务切割机制(concurrent 模式)