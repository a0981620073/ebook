# 初級大人指南書｜互動電子書網站

這是一個可直接部署到 GitHub Pages 的靜態網站。

## 檔案結構

```text
index.html
assets/ebook.pdf
README.md
```

## 部署方式

1. 到 GitHub 建立新的 repository，例如 `ebook`。
2. 將本資料夾中的 `index.html`、`assets/ebook.pdf`、`README.md` 上傳到 repository 根目錄。
3. 到 `Settings` -> `Pages`。
4. Source 選 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/root`。
6. 按 Save，等待 1-3 分鐘。
7. 網址通常會是：`https://你的帳號.github.io/ebook/`

## 功能

- Hero Section 動畫背景
- 滑鼠光暈與游標特效
- AOS / GSAP 滾動動畫
- 打字機效果
- 時間軸
- 技能條
- 作品集卡片
- Light / Dark Mode
- PDF 翻頁閱讀
- 章節跳轉、搜尋、書籤、縮放
- 響應式設計
- 聯絡表單（mailto）
