# 2026 關西之旅網站

這個版本保留目前網站外觀與互動，只把圖片移出 `index.html`。

## GitHub 結構

```text
index.html
images/
├── menu/
│   └── M001.png
├── map/
│   ├── MAP001.png
│   └── MAP002.png
├── photo/
├── hotel/
└── icon/
```

## 圖片對照表

| 完整檔名 | 路徑 | 用途 |
|---|---|---|
| `M001.png` | `images/menu/M001.png` | 神戶牛大地 Lunch Menu |
| `MAP001.png` | `images/map/MAP001.png` | 中部國際機場 第二航廈 → 第一航廈路線 |
| `MAP002.png` | `images/map/MAP002.png` | 中部國際機場官方互動地圖縮圖 |

## 更新圖片的方法

例如要換神戶牛大地菜單：

1. 新圖片命名為 `M001.png`
2. 上傳到 `images/menu/`
3. 覆蓋原本的 `M001.png`
4. 不需要修改 `index.html`

若 GitHub Pages 暫時顯示舊圖，可重新整理或稍等一分鐘。
