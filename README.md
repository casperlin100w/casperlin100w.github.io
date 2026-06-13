# 🌌 FanFan's Blog v2.0 - Aurora Evolution

[![Hexo Version](https://img.shields.io/badge/hexo-7.0+-blue.svg)](https://hexo.io/)
[![Theme](https://img.shields.io/badge/theme-Aurora-blueviolet.svg)](https://aurora.tridiamond.tech/)
[![Comment](https://img.shields.io/badge/comment-Waline-green.svg)](https://waline.js.org/)
[![Bot](https://img.shields.io/badge/bot-Dia-ff69b4.svg)](https://github.com/auroral-ui/hexo-theme-aurora)

> **追求自己所想要的一切 Everything will be alright, tomorrow will be dead.**

這是我的個人博客 **v2.0 版本**。從原本的 `LiveForCode` 主題進化為基於 Vue 3 的 **`Aurora`** 未來感主題。這裡記錄了我的技術探索、生活隨筆，以及對美感的堅持。

---

## 📅 站點日誌
*   **博主名稱**: FanFan 凡凡
*   **啟動時間**: 2026-02-12
*   **技術演進**: 
    *   **v1.0**: Hexo + LiveForCode (傳統靜態佈局)
    *   **v2.0**: Hexo + Aurora (Vue 3 SPA 單頁面應用)
*   **核心理念**: 融合流光設計、玻璃擬態與多語言互動。

---

## 🎨 特色功能與進化細節

### 1. 未來感視覺交互 (Aurora Design)
- **流光背景**: 捨棄了舊版的 Ribbon 緞帶，升級為動態漸層流光背景（`#a6cbde`, `#78ccfb`, `#a9d9af`）。
- **互動機器人**: 內建小機器人 **Dia**，針對用戶的懸停、點擊及複製行為做出動態回饋。
- **多語言切換**: 全站支持 **繁體中文 (zh-TW)** 與 **英文 (en)** 切換，包含文章內容與導航選單的同步轉換。

### 2. 閱讀與交流升級
- **評論系統**: 捨棄舊版配置，全面採用 **Waline** 服務端架構，支持表情包、回覆通知與 Vercel 部署。
- **閱讀優化**: 整合語法高亮、字數統計，並具備全語系的 SEO 元數據優化。
- **版權保護**: 內建複製保護功能，自動添加作者訊息與 CC 協議聲明。

### 3. 音樂與多媒體（繼承自 v1.0）
- **APlayer 整合**: 延續 v1.0 的本地音樂體驗，透過 `injects` 注入 APlayer 資源。
- **路徑保持**: 依舊保留 `/source/music/` 下的 `song`, `cover`, `lrc` 結構，確保存檔穩定。

### 4. 進階作品集 (Portfolio)
- **Vue 驅動**: 利用 Aurora 的 Page 模板重新建構作品集，保持深/淺色模式的完美兼容。

---

## 📁 目錄結構
```text
.
├── source/
│   ├── _posts/         # 原創文章 (按 zh-TW/ 與 en/ 目錄存放)
│   ├── image/          # 站點圖片資源 (頭像、Logo)
│   ├── music/          # 本地音樂庫 (繼承自 v1.0)
│   ├── about/          # 關於我頁面
│   └── links/          # 友情連結頁面
├── languages/          # 自定義多語言翻譯 (zh-TW.yml, en.yml)
├── _config.yml         # Hexo 全域配置
└── _config.aurora.yml  # Aurora 主題核心配置
```

---

## 📝 文章 Front-matter 規範
為了確保主題特效正常，請遵循以下格式：
```yaml
---
title: 標題
date: 2026-02-12 10:00:00
lang: zh-TW  # 重要：zh-TW 或 en
cover: /image/covers/banner.jpg # 文章封面
categories: 
  - 隨筆
tags:
  - Aurora
---
```

---

## 🔗 聯絡與社群
- **GitHub**: [casperlin100w](https://github.com/casperlin100w)
- **Instagram**: [llf._.meow](https://www.instagram.com/llf._.meow/)
- **Discord**: [加入我的伺服器](https://discord.gg/AHyeFY7v4n)
- **Twitch**: [casper_fan](https://twitch.tv/casper_fan)
- **YouTube**: [@casperlingaming](https://youtube.com/@casperlingaming/live)

---

© 2026 FanFan 版權所有 All Rights Reserved.  
*Powered by Hexo & Aurora Theme. Content assisted by Gemini.*
