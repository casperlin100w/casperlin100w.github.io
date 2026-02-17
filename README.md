# FanFan's Blog

![Hexo Version](https://img.shields.io/badge/hexo-7.0+-blue.svg)
![Theme](https://img.shields.io/badge/theme-LiveForCode-orange.svg)
![Music](https://img.shields.io/badge/player-APlayer-red.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)

---

## 📅 站點日誌
* **博主名稱**: FanFan 凡凡
- **啟動時間**: 2026-02-12
- **運行時長**: 透過 `footer.ejs` 動態計算顯示於頁尾。
- **技術棧**: Hexo 靜態網站產生器 + 自定義 LiveForCode 主題。

---

## 🎨 特色功能與客製化細節

### 1. 本地化音樂體驗 (APlayer Local)
- **存放路徑**: `/source/music/` 下設有 `song`, `cover`, `lrc` 子目錄。
- **實現方式**: 放棄第三方 API，改用本地靜態資源加載，確保音樂播放的穩定性。

### 2. 進階作品集展示 (Portfolio Page)
- **動態樣式**: 採用 Grid 佈局與自定義 CSS 效果。
- **色彩優化**: 標題支援深/淺色模式自動變色（深色模式：白色，淺色模式：深灰色 #333）。
- **交互設計**:
  - 卡片懸停動畫（Hover effect）。
  - 作品連結強制使用 `target="_blank"` 以新分頁開啟。
  - 特殊設計：標題添加文字外框（Text-stroke）與陰影，提升視覺清晰度。

### 3. 文章閱讀體驗優化
- **字數統計**: 整合 `hexo-wordcount` 外掛。
- [cite_start]**元數據顯示**: 文章標題下方及首頁列表顯示「文章長度」與「預計閱讀時間」。 [cite: 23]
- **Icon 系統**: 統一採用 FontAwesome 6.5.1 圖標，風格簡約統一。
- **目錄導航**: 整合 Tocbot，支援捲動自動高亮及平滑捲動。

### 4. 品牌視覺與特效
- **統一配色**: 全站強調色採用品牌橘色 `#fe9600`。
- **動態背景**: 支援 HomeHeader 粒線動效及 Ribbon 背景緞帶特效。
- **404 頁面**: 自定義 `icon-swimming` 游泳圖標與「PAGE NOT FOUND」導覽。

---

## 📁 主要目錄結構
```text
.
├── source/
│   ├── _posts/         # 原創文章
│   ├── portfolio/      # 作品集 index.md 與自定義樣式
│   ├── archives/       # 歸檔頁面設定檔
│   ├── image/          # 站點圖片資源 (頭像、Logo等)
│   └── music/          # 本地音樂、封面、歌詞檔
├── themes/LiveForCode/
│   ├── layout/         # 佈局文件 (container, post, footer等)
│   └── _config.yml     # 主題核心配置檔
└── _config.yml         # Hexo 全域配置檔
```
---

## 🔗 聯絡與社群
- **GitHub**: [casperlin100w](https://github.com/casperlin100w)

- **Instagram**: [llf._.meow](https://www.instagram.com/llf._.meow/)

- **Telegram**: [@luofanlin](https://t.me/luofanlin)

- **Discord**: [點我加入](https://discord.gg/AHyeFY7v4n)


© 2026 FanFan 版權所有 All Rights Reserved.

部分內容使用 Gemini 協作及編撰
