# Infinity Start

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">
  <a href="./README_EN.md">English</a> | 简体中文
</p>

---

## ✨ 简介

**Infinity Start** 是一个简洁、美观的个人浏览器起始页。采用现代化的设计风格，提供快速搜索、常用网站导航、实时时间显示等功能。

## 🚀 功能特性

- 🔍 **快速搜索** - 支持多种搜索引擎快速切换
- 🕐 **实时时钟** - 显示当前时间和日期
- 🔗 **常用导航** - 自定义常用网站快捷入口
- 🎨 **精美壁纸** - 支持自定义背景图片
- 📱 **响应式设计** - 适配各种屏幕尺寸
- ⚡ **纯前端实现** - 无需后端，部署简单

## 🛠️ 技术栈

- HTML5
- CSS3 (Flexbox + Grid)
- Vanilla JavaScript
- Google Fonts (Inter)

## 📦 项目结构

```
.
├── index.html          # 主页面
├── README.md           # 项目说明（中文）
├── README_EN.md        # 项目说明（英文）
├── .gitignore          # Git 忽略配置
└── 壁纸/               # 壁纸资源文件夹
    └── 普通/
        └── wallhaven-1j7z19.jpg
```

## 🚀 部署方式

### GitHub Pages（推荐）

1. Fork 或克隆本仓库到你的 GitHub 账号
2. 进入仓库 **Settings** → **Pages**
3. Source 选择 **Deploy from a branch**
4. Branch 选择 **master** / **main**，文件夹选择 **/(root)**
5. 点击 **Save**，等待部署完成
6. 访问 `https://你的用户名.github.io/infinity-start`

### 其他平台

本项目为纯静态网站，可部署到任何静态托管平台：
- Vercel
- Netlify
- Cloudflare Pages
- 腾讯云 COS
- 阿里云 OSS

## 📝 自定义配置

### 修改搜索引擎

编辑 `index.html` 中的搜索表单 action 属性：

```html
<form action="https://www.google.com/search" method="get">
```

### 修改背景壁纸

替换 `壁纸/普通/` 目录下的图片，并修改 CSS 中的路径：

```css
body {
    background: url('壁纸/普通/你的壁纸.jpg') center/cover no-repeat fixed;
}
```

### 添加常用网站

在 `index.html` 中找到导航区域，添加新的链接卡片：

```html
<a href="https://example.com" class="nav-card">
    <div class="nav-icon">🌐</div>
    <span class="nav-name">网站名称</span>
</a>
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

[MIT License](./LICENSE)

## 🙏 致谢

- 壁纸来源：[Wallhaven](https://wallhaven.cc)
- 字体：[Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/CCnevergiveup">CCnevergiveup</a>
</p>
