# APK HTML Website

## 🚀 Phiên bản 1.0.0 - Complete Website

Website APK với đầy đủ tính năng hiện đại và responsive design.

## ✨ Tính năng chính

### 🎯 Core Features
- **Hero Slider**: Slider tự động với dots navigation
- **Search Functionality**: Tìm kiếm với suggestions
- **Filter System**: Lọc games, apps theo category
- **Download System**: Modal xác nhận download
- **Update System**: Cập nhật apps với animation
- **Info Modal**: Hiển thị thông tin chi tiết app

### 📱 Responsive Design
- **Mobile Menu**: Hamburger menu với animation
- **Grid Layout**: Responsive grid cho cards
- **Touch Friendly**: Tối ưu cho mobile devices
- **Smooth Scrolling**: Cuộn mượt mà

### 🆕 New Features (v1.0.0)
- **Table of Contents**: Tự động tạo mục lục từ headings
- **Unfold Table**: Mở/đóng bảng với animation
- **Go Back Button**: Nút quay lại trang trước
- **Enhanced CSS**: Styling hiện đại với gradients

## 🛠️ Công nghệ sử dụng

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Animations
- **Vanilla JavaScript**: ES6+ features
- **Responsive Design**: Mobile-first approach

## 📁 Cấu trúc thư mục

```
├── assets/
│   ├── css/
│   │   ├── critical.css      # Critical CSS
│   │   ├── custome.css       # Custom styles
│   │   ├── custome.min.css   # Minified custom styles
│   │   ├── styles.css        # Main styles
│   │   └── styles.min.css    # Minified main styles
│   └── js/
│       ├── script.js         # Main JavaScript
│       └── script.min.js     # Minified JavaScript
├── images/                   # All images
├── *.html                    # HTML pages
└── README.md
```

## 🎨 CSS Features

### Entry Author Layout
- Grid layout với avatar, content và TOC button
- TOC trigger button với shadow effects

### Table of Contents
- Gradient header (tím-xanh)
- Clean white background
- Numbered headings
- Smooth scroll navigation

### Entry Cover
- Aspect ratio 3:1
- Object-fit cover
- Responsive images

## ⚡ JavaScript Features

### Core Functions
- `initializeHeroSlider()`: Hero slider functionality
- `filterGames()` / `filterApps()`: Content filtering
- `showDownloadModal()`: Download confirmation
- `showAppInfo()`: App information display

### New Functions (v1.0.0)
- `initTableOfContents()`: TOC generation
- `generateTableOfContents()`: Auto TOC from headings
- `initUnfoldTable()`: Table unfold/collapse
- `initGoBack()`: Back button functionality

## 🚀 Cách sử dụng

1. **Clone repository**
2. **Mở file `index.html`** trong browser
3. **Tất cả tính năng đã sẵn sàng sử dụng**

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## 🔧 Customization

### Thêm TOC Button
```html
<button id="toc-trigger">Show Contents</button>
<div id="table-of-content">
    <summary>Table of Contents</summary>
    <ul></ul>
</div>
```

### Thêm Go Back Button
```html
<button id="go-back">← Quay lại</button>
```

### Thêm Unfold Table
```html
<button id="unfold-table">Unfold Table</button>
<tr class="collapse-row">...</tr>
```

## 📄 License

MIT License - Sử dụng tự do cho mục đích cá nhân và thương mại.

## 👨‍💻 Developer

Created with ❤️ by MacVN

---
**Version 1.0.0** - Complete APK HTML Website