# industry-supply-chain（產業供應鏈地圖）

公開網站（GitHub Pages）的主頁面是 `index.html`，這是單一檔案，大小約 1.6 MB。

## 結構
| 路徑 | 說明 |
|---|---|
| `index.html` | 正式頁面，資料（INDUSTRIES、DIAGRAMS、SCENES、PINYIN_MAP、COMPANY_REVENUE）直接寫在檔案裡 |
| `archive/` | 舊版頁面（`index_1.html`、`supply_chain_map.html`），只留存參考，不再更新 |

## 之後的規劃
資料抽成 `data/*.json`，再用 build 腳本組回單檔。這一步還沒做。
