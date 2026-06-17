# 🏛️ 18世紀義民廟 | 閩南建築數位導覽 (Digital Exhibition)

![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.0-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white)

這是一個以「18世紀台灣歷史與閩南建築」為主題的響應式單頁網頁應用程式（SPA）。透過數位化的視覺排版與互動元件，帶領使用者探索傳統廟宇的燕尾脊、木雕工藝，以及常民生活道具（如：阿福的竹編燈籠）。

👉 **[點擊此處觀看 Live Demo (線上實機展示)](https://s93516.github.io/)**

---

## 📝 專案背景 (Project Background)

本專案為數位學習相關課程之 **期末專案 (Final Exam Project)**。
主要考核目標為：
1. 熟練運用 Bootstrap 5 框架進行前端排版。
2. 實現 RWD (響應式網頁設計)，確保在桌機與行動裝置皆有良好動線。
3. 熟悉 Git 版本控制，並成功部署至 GitHub Pages。
4. 結合個人創意，打造具備歷史敘事與沉浸感的數位展覽體驗。

---

## ✨ 核心特色與技術亮點 (Key Features)

* **沉浸式主視覺 (Hero Section)：** 運用滿版背景圖與 CSS `linear-gradient` 漸層遮罩，搭配 Noto Serif TC (思源宋體)，營造強烈的歷史氛圍與閱讀舒適度。
* **響應式網格系統 (Grid System)：** 使用 Bootstrap 5 的網格系統（`.col-md-4`, `.col-lg-8` 等），確保「建築工藝」卡片在不同螢幕尺寸下能自動流暢換行排列。
* **互動式數位文物 (Interactive Modals)：** 實作 Bootstrap Modal 彈出視窗元件，使用者點擊「竹編燈籠」即可展開無縫的文物細節與歷史背景解說。
* **平滑滾動導覽 (Smooth Scrolling & Scrollspy)：** 固定式導覽列（Sticky Navbar）結合錨點跳轉功能，提供流暢的單頁式瀏覽體驗。

---

## 🛠️ 使用技術與資源 (Technologies & Resources)

* **前端框架：** HTML5, CSS3, Bootstrap 5.3.0
* **字體與圖示：** Google Fonts (Noto Serif TC), Bootstrap Icons
* **版本控制與部署：** Git, GitHub Pages, WebStorm IDE

---

## 📂 資料夾結構 (Folder Structure)

```text
s93516.github.io/
│
├── images/               # 存放真實展覽圖片與文物視覺
│   ├── 1.jpg             # 建築特色：燕尾脊
│   ├── 2.jpg             # 建築特色：木雕斗栱
│   ├── 3.jpg             # 建築特色：石雕龍柱
│   ├── 4.jpg             # 重點文物：阿福的竹編燈籠
│   └── 5.jpg             # 首頁滿版主視覺背景圖
│
├── index.html            # 網站主程式 (單頁面入口)
└── README.md             # 專案說明文件
