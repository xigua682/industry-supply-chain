# 編輯規則（bot 和 Claude 都要遵守）

1. 只改根目錄的 `index.html`。`archive/` 裡是舊版，不要改，也不要當成來源。
2. 這是公開 repo，不能放付費內容（定錨、曼報）、帳號、金鑰或客戶資料。
3. 改資料時，只動對應的資料常數（INDUSTRIES、DIAGRAMS、SCENES、PINYIN_MAP、COMPANY_REVENUE），不要重排或格式化整個檔案，避免 diff 變得巨大。
4. 改完先用瀏覽器打開，確認主控台沒有錯誤、地圖和搜尋都正常。
5. 用 git commit 並寫清楚訊息（說明改了哪個產業或公司），不要再用網頁「Add files via upload」上傳。
6. push 前要先跟 Jerry 確認；不刪檔、不 force push、不改 repo 設定。
