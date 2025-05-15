# Airbnb 風格預訂頁面

這是一個模仿 Airbnb 風格的預訂頁面專案，使用 Bootstrap 5 實現響應式網頁設計（RWD）。頁面針對手機、平板和桌面裝置進行了優化。

## 功能特點

- 基於 Bootstrap 5 框架構建
- 完全響應式設計，適配不同尺寸的設備
- 簡潔現代的 UI 設計
- 包含導航欄、篩選器、列表和頁腳區域
- 提供 4 列佈局的物品卡片

## 技術堆疊

- HTML5
- CSS3
- Bootstrap 5
- Font Awesome 圖標

## 開始使用

### 安裝依賴

```bash
npm install
```

### 啟動開發伺服器

```bash
npm start
```

此命令將在 http://localhost:3000 啟動一個本地服務器。

## 項目結構

```
booking-page/
├── css/
│   └── style.css
├── index.html
├── package.json
└── README.md
```

## 響應式設計

該專案針對以下螢幕尺寸提供了優化：

- **手機螢幕**（< 576px）：單列卡片佈局
- **平板螢幕**（576px - 768px）：雙列卡片佈局
- **桌面螢幕**（> 768px）：四列卡片佈局

## 定制

您可以通過修改 `css/style.css` 文件來自定義網站的外觀和感覺。主要的顏色變數定義在 CSS 文件的開頭：

```css
:root {
    --primary-color: #FF5A5F;
    --primary-dark: #FF385C;
    --text-muted: #717171;
    --border-color: #DDDDDD;
}
```

## 授權

MIT 授權 