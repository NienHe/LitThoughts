# LitThoughts

LitThoughts 是一個讀書的社群網站，名字 Lit 取自 Literary(文學)的簡寫，Thoughts為想法。這個平台提供使用者發表書籍讀後心得，分享閱讀感悟和體會，其他用戶也可以對這些貼文按讚、評論，促進讀者們的交流與互動。

網站連結：[https://www.litthoughts.com](https://www.litthoughts.com)

## 專案動機

2024年04月開始想學習後端到全端的技術，所以發想這個idea，做成一個side project。開發過程中覺得很有趣，也希望能夠打造成功能完善的平台，使得每一篇貼文都可以讓不同的讀者互相得到啟發，提升思維的深度和廣度。

## 專案功能

- **登入註冊**：使用者可以註冊帳號使用平台功能，另外也會提供訪客瀏覽模式。
- **發貼文**：使用者可以發佈與書籍相關的讀後心得或感悟。
- **按讚**：用戶可以彼此對貼文表示讚同和支持。
- **評論**：使用者可以對貼文進行評論，表達自己的看法和意見。
- **排行榜**：實時統計按讚數和評論數，取前五篇貼文列入排行推薦給其他用戶。

## 專案架構

LitThoughts 主要分成以下四個部分，同時在此Repo也記錄相關技術的學習筆記。

### 1. Frontend

- **框架**：Vue.js
- **功能**：實現使用者介面、貼文展示、按讚和評論功能。
- **樣式**：使用 HTML 和 CSS 進行頁面佈局和樣式設計。

### 2. Backend

- **框架**：Java Spring Boot
- **功能**：提供前端 API 接口、處理使用者請求、串接第三方API、進行資料處理和邏輯實作。
- **安全性**：實現使用者身份驗證和授權，確保資料安全。

### 3. Database

- **資料庫**：MySQL
- **功能**：儲存使用者資訊、貼文、評論和按讚記錄。
- **結構**：設計合理的資料表結構，設定索引和外鍵，提高查詢效率。

### 4. Amazon Web Service(AWS)

- **運算平台**：AWS EC2
- **功能**：部署和運行後端服務，配置 Apache 伺服器，設定網域發佈上線。
- **安全性**：設定 HTTPS及防火牆，確保資料傳輸的安全性。

