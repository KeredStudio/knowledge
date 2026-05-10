# 知識典藏 · Knowledge

> *「沒有音樂，生命將是一個錯誤。」——尼采*

一個以靜態網頁呈現的知識整理計畫。每個主題都是一個獨立的沉浸式頁面，設計上追求可讀性與美感的平衡。

---

## 收錄內容

### 哲學

| 頁面 | 主題 | 語言 | 連結 |
|------|------|------|------|
| `nietzsche.html` | 弗里德里希·尼采——生平、哲學、著作、語錄與影響 | 繁體中文 | [查看](./nietzsche.html) |

---

## 設計理念

- **單檔完整** — 每個主題是一個自含的 `.html` 檔案，無需伺服器、無需框架，下載即可離線閱覽
- **沉浸式排版** — 深色底、金色點綴、襯線字體，讓閱讀本身成為一種體驗
- **捲動動畫** — 以 Intersection Observer 驅動的滾動顯現效果，保持輕量無依賴
- **響應式設計** — 桌面與行動裝置皆可良好呈現

---

## 本地預覽

直接用瀏覽器開啟 `.html` 檔案即可：

```bash
open nietzsche.html   # macOS
```

或透過本地伺服器：

```bash
python3 -m http.server 8080
# 開啟 http://localhost:8080/nietzsche.html
```

---

## 技術棧

- 純 HTML / CSS / JavaScript，零外部依賴（除 Google Fonts）
- 字體：Cinzel · Cormorant Garamond · Noto Serif TC
- 動畫：CSS Keyframes + Intersection Observer API

---

## 即將收錄

- 斯多葛哲學 — 馬可·奧理略、愛比克泰德、塞內卡
- 存在主義 — 沙特、卡繆、海德格
- 東方哲學 — 老子、莊子、佛陀

---

<sub>以繁體中文書寫。內容僅供學習與欣賞用途。</sub>
