# Matsu GoGoGo｜馬祖旅遊網站

這是重新整理後的 GitHub Pages 專案版本。

## 特色

- 單檔式 `index.html`
- 不需要 css / js / data 資料夾
- 避免 GitHub Pages 載入 CSS/JS 失敗
- 支援手機瀏覽
- 內建 Google Maps 導航
- 內建船班/訂票連結
- 內建花費計算
- 內建打卡清單與完成度

## 建立新 GitHub 專案流程

1. 到 GitHub 建立新的 Repository
2. Repository 建議名稱：
   `matsugogogo`
3. 設定為 Public
4. 上傳本資料夾內的：
   - `index.html`
   - `README.md`
5. 到 Settings → Pages
6. Source 選擇 Deploy from a branch
7. Branch 選 main
8. Folder 選 /root
9. Save
10. 等待 30 秒～2 分鐘

網址會類似：

`https://你的帳號.github.io/matsugogogo/`

## 修改方式

所有內容都在 `index.html` 裡。

可搜尋：
- `ITINERARY`：修改每日行程
- `PLACES`：修改景點、餐廳、導航、營業時間
- `transport`：修改船班/訂票連結
