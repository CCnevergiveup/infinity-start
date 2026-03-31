# Infinity Start

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">
  English | <a href="./README.md">简体中文</a>
</p>

---

## ✨ Introduction

**Infinity Start** is a clean and beautiful personal browser start page. It features a modern design style with quick search, frequently used website navigation, real-time clock display, and more.

## 🚀 Features

- 🔍 **Quick Search** - Support for multiple search engines with quick switching
- 🕐 **Real-time Clock** - Display current time and date
- 🔗 **Quick Navigation** - Customizable shortcuts for frequently visited websites
- 🎨 **Beautiful Wallpapers** - Support for custom background images
- 📱 **Responsive Design** - Adaptable to various screen sizes
- ⚡ **Pure Frontend** - No backend required, easy to deploy

## 🛠️ Tech Stack

- HTML5
- CSS3 (Flexbox + Grid)
- Vanilla JavaScript
- Google Fonts (Inter)

## 📦 Project Structure

```
.
├── index.html          # Main page
├── README.md           # Project documentation (Chinese)
├── README_EN.md        # Project documentation (English)
├── .gitignore          # Git ignore configuration
└── 壁纸/               # Wallpaper resources folder
    └── 普通/
        └── wallhaven-1j7z19.jpg
```

## 🚀 Deployment

### GitHub Pages (Recommended)

1. Fork or clone this repository to your GitHub account
2. Go to repository **Settings** → **Pages**
3. Select **Deploy from a branch** as the Source
4. Choose **master** / **main** branch, folder **/(root)**
5. Click **Save** and wait for deployment
6. Visit `https://your-username.github.io/infinity-start`

### Other Platforms

This is a pure static website that can be deployed to any static hosting platform:
- Vercel
- Netlify
- Cloudflare Pages
- Tencent Cloud COS
- Alibaba Cloud OSS

## 📝 Customization

### Change Search Engine

Edit the form action attribute in `index.html`:

```html
<form action="https://www.google.com/search" method="get">
```

### Change Background Wallpaper

Replace the image in `壁纸/普通/` directory and update the CSS path:

```css
body {
    background: url('壁纸/普通/your-wallpaper.jpg') center/cover no-repeat fixed;
}
```

### Add Frequently Used Websites

Find the navigation section in `index.html` and add new link cards:

```html
<a href="https://example.com" class="nav-card">
    <div class="nav-icon">🌐</div>
    <span class="nav-name">Website Name</span>
</a>
```

## 🤝 Contributing

Issues and Pull Requests are welcome!

## 📄 License

[MIT License](./LICENSE)

## 🙏 Acknowledgments

- Wallpaper source: [Wallhaven](https://wallhaven.cc)
- Font: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/CCnevergiveup">CCnevergiveup</a>
</p>
