# 2026 關西之旅網站

目前網站版本：`v16.05`

圖片統一存放於 `images/`，避免把圖片資料直接寫進 `index.html`。餐廳菜單與地圖圖片可使用共用相簿檢視器放大查看。

## GitHub 結構

```text
index.html
README.md
images/
├── menu/
│   ├── M001.png
│   ├── M002.png
│   ├── M003.png
│   ├── M004.png
│   ├── M005.png
│   ├── M006.png
│   ├── M007.png
│   ├── M008.png
│   ├── M009.png
│   ├── M007.png
│   ├── M008.png
│   ├── M009.png
│   ├── M010.png
│   ├── M011.png
│   ├── M012.png
│   ├── M013.png
│   ├── M014.png
│   ├── M015.png
│   └── M016.png
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
| `M002.png` | `images/menu/M002.png` | 馬喰一代名古屋 EAST－王道炭火燒套餐 |
| `M003.png` | `images/menu/M003.png` | 馬喰一代名古屋 EAST－王道炭火燒肉（單點） |
| `M004.png` | `images/menu/M004.png` | 馬喰一代名古屋 EAST－逸品料理 |
| `M005.png` | `images/menu/M005.png` | 馬喰一代名古屋 EAST－主食・湯品・甜點 |
| `M006.png` | `images/menu/M006.png` | 徳川町ぶた福－固定菜單翻譯 |
| `M007.png` | `images/menu/M007.png` | 徳川町ぶた福－今日限定菜單指南 |
| `M008.png` | `images/menu/M008.png` | 徳川町ぶた福－飲料菜單翻譯 |
| `M009.png` | `images/menu/M009.png` | BUCYO COFFEE 早餐套餐 |
| `M010.png` | `images/menu/M010.png` | BUCYO COFFEE 飲品 |
| `M011.png` | `images/menu/M011.png` | BUCYO COFFEE 簡餐 |
| `M012.png` | `images/menu/M012.png` | BUCYO COFFEE 甜點 |
| `M013.png` | `images/menu/M013.png` | BUCYO COFFEE 三明治＆沙拉 |
| `M014.png` | `images/menu/M014.png` | BUCYO COFFEE 三明治 |
| `M015.png` | `images/menu/M015.png` | BUCYO COFFEE 下午義大利麵 |
| `M016.png` | `images/menu/M016.png` | BUCYO COFFEE 霜淇淋 |
| `MAP001.png` | `images/map/MAP001.png` | 中部國際機場 第二航廈 → 第一航廈路線 |
| `MAP002.png` | `images/map/MAP002.png` | 中部國際機場官方互動地圖縮圖 |

## 上傳／更新圖片的方法

例如要加入徳川町ぶた福的三張菜單：

1. 將三張圖片依序命名為 `M006.png`、`M007.png`、`M008.png`。
2. 上傳到 `images/menu/`。
3. 若已有同名檔案，直接覆蓋。
4. 不需要修改 `index.html`。

新增圖片時請使用下一個未使用的編號，不要重複使用或重新排列舊編號。即使某張圖片日後停用，也保留原編號，避免既有 HTML 連結失效。

## 圖片相簿功能

同一間餐廳的多張菜單會被視為同一組相簿：

- 點擊縮圖可放大。
- 手機可左右滑動切換上一張／下一張。
- 電腦可使用左右方向鍵或畫面兩側箭頭切換。
- 畫面會顯示目前張數，例如 `2 / 3`。
- 雙擊圖片可關閉。
- 也可使用右上角 `×`、點擊黑色背景或按 `Esc` 關閉。
- 可切換「適合畫面／原始尺寸」查看細節。

若圖片載入失敗，請確認：

- 檔名大小寫完全一致。
- 圖片放在正確資料夾。
- HTML 內路徑與上方圖片對照表相符。

## GitHub Pages 快取

首頁右下角會顯示低調版本號，例如 `v16.02`，可用來確認 GitHub Pages 是否已更新。

若仍顯示舊版本，可強制重新整理，或稍等一分鐘後再查看。若只覆蓋圖片但快取長時間未更新，可調整 HTML 圖片網址後方的快取版本參數，例如由 `?v=1` 改為 `?v=2`。
