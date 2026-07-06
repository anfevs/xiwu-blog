---
title: 'Tailwind CSS 使用心得'
description: '分享在实际项目中使用 Tailwind CSS 的一些经验和技巧'
pubDate: '2026-06-25'
tags: ['CSS', 'Tailwind', '前端']
category: '技术'
---

## 为什么用 Tailwind

工具类优先的 CSS 框架，让样式编写更高效。

## 常用技巧

### 响应式设计

使用断点前缀轻松实现响应式：

```html
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3">
```

### 暗色模式

通过 `dark:` 变体支持暗色模式：

```html
<div class="bg-white dark:bg-gray-900">
```

### 自定义主题

在 `@theme` 中定义项目专属的设计令牌。
