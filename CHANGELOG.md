# CHANGELOG

## 2026-07-21
- 保留目前 UI 與單一 `index.html`
- 圖片改成外部檔案
- 新增固定編號：
  - `M001.png`
  - `MAP001.png`
  - `MAP002.png`

## 2026-07-21 修正
- 修正圖片 Lightbox 在 GitHub Pages 點擊無反應
- 原因：JavaScript 執行時 Lightbox 元素尚未載入
- 將所有互動初始化統一放入 DOMContentLoaded
