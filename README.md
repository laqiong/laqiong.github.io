# 像企业家一样写作

> 用写作重新定义你的事业

这是 [laqiong.github.io](https://laqiong.github.io) 的源码仓库。

## 网站结构

- `index.html` — 首页
- `about.html` — 关于
- `blog.html` — 博客列表
- `course.html` — 课程销售页
- `contact.html` — 联系
- `_posts/` — 博客文章（Markdown）

## 如何写新文章

在 `_posts/` 目录下新建一个 Markdown 文件，命名格式：

```
YYYY-MM-DD-文章标题.md
```

文件头部需要包含：

```yaml
---
layout: post
title: "文章标题"
date: YYYY-MM-DD HH:MM:SS +0800
tags: [标签1, 标签2]
reading_time: "X 分钟"
---
```

然后提交并推送到 GitHub，GitHub Pages 会自动更新网站。

## 技术栈

- Jekyll（GitHub Pages 原生支持）
- 手写 CSS（Notion 风格）
- 无依赖，加载极快

## 本地预览

```bash
bundle install
bundle exec jekyll serve
# 访问 http://localhost:4000
```

## License

MIT
