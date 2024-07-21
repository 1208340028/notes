---
title: react
date: 2024-05-03 07:42:40
permalink: /pages/4d131b/
sidebar: auto
categories:
  - 随笔
tags:
  - 
author: 
  name: 执迷
  link: https://github.com/1208340028
---
## react哲学
- 按ui来划分组件层级
- 
## 组件
- 组件首字母必须大写

##  props（属性）

- react的组件属性是只读的

## stats（状态）
- 状态是可改的

## 声明周期
- 创建时（componentDidMount）
    - constructor
    - render
- 更新时（componentDidUpdate）
    - 更新Dom
    - new Props
    - setState
    - forceUpdate
- 卸载时（componentWillUnmount）
