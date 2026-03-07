# 咸鱼的技术博客

基于 Hugo + PaperMod 主题搭建的个人技术博客。

## 🚀 快速开始

### 本地预览
\`\`\`bash
cd my-blog
~/bin/hugo server -D
# 访问 http://localhost:1313
\`\`\`

### 创建新文章
\`\`\`bash
~/bin/hugo new content posts/my-new-article.md
\`\`\`

### 构建静态文件
\`\`\`bash
~/bin/hugo --minify
# 生成的文件在 public/ 目录
\`\`\`

## 📁 目录结构

\`\`\`
my-blog/
├── archetypes/          # 文章模板
├── content/             # 博客内容
│   └── posts/          # 文章目录
├── themes/             # 主题
│   └── PaperMod/      # 当前使用的主题
├── hugo.toml          # Hugo配置文件
└── public/            # 生成的静态文件
\`\`\`

## ✍️ 写作流程

1. 创建新文章: \`~/bin/hugo new content posts/article-name.md\`
2. 编辑文章: 使用Markdown格式编写
3. 本地预览: \`~/bin/hugo server -D\`
4. 发布: 构建并部署到服务器或GitHub Pages

## 🌐 部署

### 方式1: GitHub Pages
1. 推送到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择部署分支和目录

### 方式2: 云服务器
1. 构建: \`~/bin/hugo --minify\`
2. 配置Nginx指向 \`public/\` 目录
3. 或使用简单的HTTP服务器

## 📝 文章模板

文章头部需要包含Front Matter:

\`\`\`markdown
+++
date = '2026-03-07T16:39:28+08:00'
draft = false
title = '文章标题'
tags = ["标签1", "标签2"]
categories = ["分类"]
+++

这里是正文内容...
\`\`\`

## 🔧 配置

主要配置在 \`hugo.toml\` 文件中:
- 站点标题和描述
- 主题设置
- 导航菜单
- 社交链接

## 📚 相关链接

- [Hugo官方文档](https://gohugo.io/documentation/)
- [PaperMod主题文档](https://github.com/adityatelange/hugo-PaperMod)
- [Markdown语法指南](https://www.markdownguide.org/)

## 📊 博客状态

- **Hugo版本**: v0.146.0
- **主题**: PaperMod
- **状态**: ✅ 运行中
- **本地访问**: http://localhost:1313
- **服务器访问**: http://101.32.114.14:1313 (如果端口开放)

---

Happy Writing! ✨
