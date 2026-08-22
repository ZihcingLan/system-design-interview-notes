# System Design Interview 中文互動筆記

《[System Design Interview: An Insider's Guide](https://bytes.usc.edu/~saty/courses/docs/data/SystemDesignInterview.pdf)》(Alex Xu 著)的繁體中文讀書筆記。

每一章都是一個獨立的互動式網頁:藍圖風格排版、可拖拉/可點擊的圖解與試算器,加上一些書本以外、有助於理解的業界真實案例(可折疊,不看也不影響閱讀主線)。

## 🔗 線上閱讀

啟用 GitHub Pages 後(見下方設定方式),可以直接用瀏覽器打開,不用下載檔案:

```
https://zihcinglan.github.io/system-design-interview-notes/
```

## 📖 章節進度

| # | 章節 | 筆記 | 狀態 |
|---|---|---|---|
| 1 | Scale From Zero To Millions Of Users | [chapter1_blueprint_notes.html](chapter1_blueprint_notes.html) | ✅ |
| 2 | Back-of-the-Envelope Estimation | [chapter2_estimation_notes.html](chapter2_estimation_notes.html) | ✅ |
| 3 | A Framework for System Design Interviews | [chapter3_framework_notes.html](chapter3_framework_notes.html) | ✅ |
| 4 | Design a Rate Limiter | [chapter4_ratelimiter_notes.html](chapter4_ratelimiter_notes.html) | ✅ |
| 5 | Design Consistent Hashing | — | ⬜ |
| 6 | Design a Key-Value Store | — | ⬜ |
| 7 | Design a Unique ID Generator in Distributed Systems | — | ⬜ |
| 8 | Design a URL Shortener | — | ⬜ |
| 9 | Design a Web Crawler | — | ⬜ |
| 10 | Design a Notification System | — | ⬜ |
| 11 | Design a News Feed System | — | ⬜ |
| 12 | Design a Chat System | — | ⬜ |
| 13 | Design a Search Autocomplete System | — | ⬜ |
| 14 | Design YouTube | — | ⬜ |
| 15 | Design Google Drive | — | ⬜ |
| 16 | The Learning Continues | — | ⬜ |

## ✨ 特色

- **互動式圖解**:每章有一個可操作的核心元件,例如第一章的架構演化滑桿、第二章的 QPS/儲存空間試算器、第四章的限流演算法模擬器,不是靜態截圖。
- **業界真實案例**:額外補充書本以外、跟該章觀念對應的真實公司案例(GitHub、Netflix、Instagram、Stripe、Cloudflare…),用折疊區塊呈現,自由選看。
- **統一藍圖視覺風格**:深藍工程藍圖配色 + 等寬字體,所有章節排版一致。

## 📁 檔案結構

```
system-design-interview-notes/
├── index.html                          # 目錄首頁,列出所有章節
├── chapter1_blueprint_notes.html
├── chapter2_estimation_notes.html
├── chapter3_framework_notes.html
├── chapter4_ratelimiter_notes.html
└── README.md
```

每章都是**單一、自包含的 HTML 檔**(CSS/JS 都寫在檔案內),可以直接雙擊在瀏覽器打開,不需要安裝任何東西。之後每完成一章,只要新增一個 `chapterN_xxx.html` 檔案,並在 `index.html` 加一行連結即可。

## 🛠 如何啟用 GitHub Pages

1. 進入 repo 的 **Settings → Pages**
2. Source 選擇 `main` branch、`/ (root)`
3. 儲存後等待幾分鐘,即可透過上方網址線上瀏覽

## ⚠️ 版權聲明

本專案為個人閱讀筆記,內容整理自 Alex Xu 所著《System Design Interview: An Insider's Guide》,僅供個人學習使用。書中原文、圖表版權屬原作者所有;本筆記中的圖解與試算器為重新繪製/開發的原創內容,並非書中掃描圖片。
