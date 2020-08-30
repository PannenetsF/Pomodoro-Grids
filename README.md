# Pomodoro-Grids
以后填坑！

## 起因

一直在用 Super Productivity 这个软件，总体上满足了我日常的需求：
- 番茄钟
- 任务规划+重复
- 一定的数据分析能力

但是这个软件也存在一定的问题：
- 上手不是很友好，有一系列的机制如 Backlog, Today, Project 等
- 英语以及中文的翻译有点令人费解
- 日常的崩溃

## 期望

用 Vue.js + Electron 开发，打包成 Appimage ，有人用的话再打包到 .exe 和 .dmg （想 peach）。

## 功能

基本框架会参考 Super Productivity

- 提供 Today ：存储今日任务以及拖延任务
- 提供 Project ：存储归属于特定集合的任务，会自动在 Today 显示
- 提供 Calendar ：表示目前已规划的任务，可以以月为单位，以周为单位
- 提供 Overview ：对特定 Project 或全局做评估，提供逐个任务，逐天，逐周，逐月，逐 Project 的总结，支持导出
- 提供 Timer ：默认使用番茄钟，可以设置时间等信息
- 提供语言接口
- 提供主题颜色配置方案
- 提供 gist 备份
- 提供插件接口： 在任务详情页添加框，在全局添加框，对数据进行二次处理等
  - 元数据属于 Project ，在 Today 直接添加的数据归为 Unnamed Project
  - Timer 属于元插件
  - Today 属于插件
  - Calendar 属于插件
  - Overview 属于插件
  