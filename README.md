### 说明

RicardoPang 的个人博客 [博客地址](https://blackwhiteandgray.github.io)

### 撰写博文

要发表的文章一般以 **Markdown** 的格式放在这里`_posts/`，你只要看看这篇模板里的文章你就立刻明白该如何设置。

yaml 头文件长这样:

```
---
layout:     post
title:      主标题
subtitle:   副标题
date:       1999-12-31
author:     BY
header-img: img/post-bg-ios9-web.jpg
catalog: 	 true
tags:
    - 前端
---

```

### 部署说明

本博客可以部署在以下平台：

1. **GitHub Pages**：通过推送到 GitHub 仓库自动部署

2. **Vercel 部署**：
   - 在 Vercel 上导入该仓库
   - Vercel 会自动识别为 Jekyll 项目并使用正确的构建命令
   - 构建配置已在 `vercel.json` 文件中设置
   - 依赖项已在 `Gemfile` 中指定

如果在部署过程中遇到问题，请检查：

- Jekyll 版本兼容性
- Ruby 依赖是否正确安装
- `_config.yml` 中的配置是否正确
