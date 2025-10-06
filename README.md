# NoJsCarousel

一個簡單、無 JavaScript 的圖片輪播組件，使用純 CSS 和 HTML 實現。

## 功能特色

- 🚀 **無 JavaScript**：完全使用 CSS 實現，無需 JavaScript 依賴
- 📱 **響應式設計**：支援桌面和移動設備
- ♿ **無障礙支援**：包含 ARIA 標籤和語意化 HTML
- 🎨 **自訂樣式**：使用 CSS 變數輕鬆調整顏色主題
- ⚡ **性能優化**：使用 `loading="lazy"` 和預載圖片
- 🎯 **現代 CSS**：運用 CSS Scroll Snap 和 Scroll Marker 等新特性

## 技術棧

- HTML5
- CSS3 (使用現代特性如 Scroll Snap, Scroll Marker, CSS Anchor Positioning)

## 瀏覽器支援

- Chrome 121+
- Firefox 121+
- Safari 17.4+

## 使用方法

1. 下載或複製 `index.html` 和 `styles.css` 文件
2. 在 HTML 中修改圖片來源或添加更多卡片
3. 在 `styles.css` 中調整 CSS 變數來自訂顏色主題

## 自訂

### 顏色主題

在 `:root` 中修改以下 CSS 變數：

```css
:root {
	--card-bg-color: #35414f; /* 卡片背景色 */
	--background-color: #121212; /* 頁面背景色 */
	--text-color: #ffffff; /* 文字顏色 */
	--arrow-color: #225452; /* 箭頭按鈕顏色 */
	--dot-color: #343e3e; /* 指示點顏色 */
	--dot-active-color: #008783; /* 活躍指示點顏色 */
}
```

### 添加更多圖片

在 `index.html` 的 `.carousel` 容器中添加更多 `.card` 元素：

```html
<div class="card" id="card13">
	<img src="your-image-url.jpg" alt="描述文字" loading="lazy" />
</div>
```

## 授權

MIT License

## 貢獻

歡迎提交 Issue 和 Pull Request！
