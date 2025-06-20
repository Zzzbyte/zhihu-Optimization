# 知乎排版优化（知乎阅读增强脚本）

## 简介

这是一个适用于知乎网页的油猴脚本，用于优化知乎的阅读排版体验。它会隐藏右侧栏、拉宽主内容区域、取消顶部导航栏的固定，使阅读更加专注和清爽。

## 功能

- 自动隐藏首页、热榜、关注页、问题页、用户页、搜索页等右侧边栏
- 自动调整主内容区左右边距，更适合宽屏显示器
- 顶部导航栏在滚动时取消固定，减少遮挡

## 使用方法

1. 安装浏览器扩展：[Tampermonkey（油猴）](https://www.tampermonkey.net/)
2. 点击安装脚本：[知乎排版优化.user.js](https://update.greasyfork.org/scripts/21659/%E7%9F%A5%E4%B9%8E%E6%8E%92%E7%89%88%E4%BC%98%E5%8C%96.user.js)
3. 打开知乎相关页面（如 https://www.zhihu.com/question/xxx），即可看到排版优化效果。

## 脚本适配页面

- `https://www.zhihu.com/`
- `https://www.zhihu.com/follow`
- `https://www.zhihu.com/hot`
- `https://www.zhihu.com/question/*`
- `https://www.zhihu.com/people/*`
- `https://www.zhihu.com/search?*`

## 示例截图

> （如有截图可插入此处）

## 开发者说明

本脚本主要使用 JavaScript + DOM 操作，基于 Tampermonkey 用户脚本环境。你可以自由修改自定义边距和隐藏模块以满足个人喜好。


