# 0xseanlee | Terminal Hub 🖥️

[![Status](https://img.shields.io/badge/STATUS-ONLINE-00ff00?style=flat-for-the-badge&logo=statuspage&logoColor=00ff00&labelColor=000000&color=00ff00)](https://0xseanlee.github.io/)
[![Secure Level](https://img.shields.io/badge/SECURE__LEVEL-MAXIMUM-white?style=flat-for-the-badge&labelColor=000000&color=00ff00)](https://0xseanlee.github.io/)

> Welcome to the matrix. 這是 0xseanlee 的極客自介空間與專案集散地。

本專案採用 **Tailwind CSS**、**AOS 動畫庫** 與 **Font Awesome 圖標** 深度打造，具備高對比的高級感終端機黑客視覺風格（Matrix Glow & Borders），並實現了資料與排版分離的動態渲染架構。

---

## 🛠️ 核心架構與動態載入

本首頁整合了資料分離技術，所有的網頁作品與專案卡片皆透過 JavaScript (`fetch`) 在網頁載入時即時向 `./app.json` 讀取並渲染。

### 📂 檔案結構
```text
0xseanlee.github.io/
├── index.html         # 核心渲染引擎 (前端網頁主體)
├── app.json           # 作品資料庫 (集中管理專案與工具)
├── sitemap.xml        # SEO 搜尋引擎導航地圖
└── README.md          # 本說明文件
