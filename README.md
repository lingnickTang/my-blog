# 思源的哲学与技术思考

这是一个基于 Jekyll 的个人博客，专注于哲学思考、技术探索和个人成长的分享。

## 🌟 特性

- 📝 **优雅的写作体验** - 支持 Markdown 写作
- 🎨 **现代化设计** - 响应式布局，支持多种设备
- 🏷️ **分类标签系统** - 方便组织和查找文章
- 🔍 **SEO 优化** - 搜索引擎友好
- 🚀 **快速部署** - 支持 GitHub Pages 免费托管
- 📱 **移动端友好** - 完美适配手机和平板

## 🛠️ 技术栈

- **Jekyll** - 静态站点生成器
- **Liquid** - 模板语言
- **Sass/CSS** - 样式设计
- **JavaScript** - 交互功能
- **GitHub Pages** - 免费托管

## 🚀 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/yourusername/myrepo.git
cd myrepo
```

### 2. 安装依赖

确保你已经安装了 Ruby 和 Bundler：

```bash
# 安装 Jekyll 和其他依赖
bundle install
```

### 3. 本地运行

```bash
bundle exec jekyll serve
```

访问 `http://localhost:4000` 查看博客

### 4. 开发模式

```bash
bundle exec jekyll serve --livereload
```

这将启用自动重载，修改文件后浏览器会自动刷新。

## 📁 项目结构

```
myrepo/
├── _config.yml          # Jekyll 配置文件
├── _layouts/            # 页面布局模板
│   ├── default.html     # 默认布局
│   ├── post.html        # 文章页面布局
│   └── page.html        # 静态页面布局
├── _includes/           # 可复用组件
│   ├── header.html      # 网站头部
│   └── footer.html      # 网站底部
├── _posts/              # 博客文章
│   ├── 2025-01-07-philosophical-reflections-on-technology.md
│   ├── 2025-01-06-habit-formation-and-self-discipline.md
│   └── 2025-01-05-academic-research-and-life-balance.md
├── assets/              # 静态资源
│   ├── css/style.css    # 样式文件
│   └── js/main.js       # JavaScript 文件
├── pages/               # 静态页面
│   ├── about.md         # 关于页面
│   ├── posts.html       # 所有文章
│   └── categories.html  # 分类页面
├── index.html           # 首页
├── Gemfile              # Ruby 依赖
└── README.md            # 项目说明
```

## ✍️ 写作指南

### 创建新文章

1. 在 `_posts/` 目录下创建新的 Markdown 文件
2. 文件名格式：`YYYY-MM-DD-title.md`
3. 添加 Front Matter：

```yaml
---
layout: post
title: "文章标题"
date: 2025-01-07 20:30:00 +0800
categories: ["分类1", "分类2"]
tags: [标签1, 标签2, 标签3]
author: 思源
---

文章内容...
```

### 支持的分类

- **哲学思考** - 对人生、社会、存在的深度思考
- **技术探索** - 编程、算法、技术研究心得
- **个人成长** - 习惯培养、自我提升、学习方法
- **社会观察** - 时事评论、社会现象分析

### Markdown 语法支持

- 标题、段落、列表
- 代码块和行内代码
- 引用块
- 表格
- 链接和图片
- 数学公式（LaTeX）

## 🎨 自定义配置

### 修改基本信息

编辑 `_config.yml` 文件：

```yaml
title: "你的博客标题"
description: "你的博客描述"
author: "你的名字"
email: "your-email@example.com"
url: "https://yourusername.github.io"
baseurl: "/your-repo-name"
```

### 修改导航菜单

在 `_config.yml` 的 `navigation` 部分添加或修改菜单项：

```yaml
navigation:
  - title: "首页"
    url: /
  - title: "文章"
    url: /posts/
  - title: "关于"
    url: /about/
```

### 自定义样式

- 主要样式文件：`assets/css/style.css`
- 支持 Sass 变量和嵌套语法
- 响应式设计，支持移动端

## 🚀 部署到 GitHub Pages

### 1. 创建 GitHub 仓库

- 仓库名可以是任意名称（如 `my-blog`）
- 设置为公开仓库

### 2. 推送代码

```bash
git add .
git commit -m "Initial commit"
git push origin main
```

### 3. 启用 GitHub Pages

- 进入仓库设置页面
- 找到 "Pages" 部分
- 选择 "Source" 为 "Deploy from a branch"
- 选择分支为 `main`，文件夹为 `/ (root)`
- 点击 "Save"

### 4. 访问博客

几分钟后，你的博客将在 `https://yourusername.github.io/your-repo-name` 上线。

## 🔧 高级功能

### 评论系统

可以集成第三方评论系统，如：
- Disqus
- Gitalk
- Utterances

### 统计分析

添加 Google Analytics 或其他分析工具：

```yaml
# _config.yml
google_analytics: UA-XXXXXXXXX-X
```

### RSS 订阅

博客自动生成 RSS 订阅源：`/feed.xml`

### 搜索功能

可以添加客户端搜索功能，支持按标题、内容、标签搜索。

## 🤝 贡献指南

欢迎提交问题和改进建议！

1. Fork 项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

## 📄 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 🙏 致谢

感谢以下开源项目和资源：

- [Jekyll](https://jekyllrb.com/) - 静态站点生成器
- [GitHub Pages](https://pages.github.com/) - 免费托管服务
- [Font Awesome](https://fontawesome.com/) - 图标字体
- [Google Fonts](https://fonts.google.com/) - 网页字体

## 📞 联系方式

- 邮箱：your-email@example.com
- GitHub：[@yourusername](https://github.com/yourusername)
- 博客：https://yourusername.github.io/myrepo

---

**开始你的写作之旅吧！** 🚀 