# 爆款短影音｜前三秒留人大挑戰

以 GitHub Pages 發布的純前端互動學習遊戲。學生透過情境選擇題，練習辨認開場的吸引力，作答後閱讀解析並獲得分數。

## 本機預覽

直接用瀏覽器開啟 `index.html`，或在此資料夾啟動簡單靜態伺服器。

## 網站網址

本工具放在既有 GitHub Pages 專案的 `copywriting-observation-game/` 資料夾：

`https://leonyang0512-stack.github.io/self-media-positioning-game/copywriting-observation-game/`

更新 `main` 分支後，GitHub Pages 會部署最新內容。

## 修改題目

開啟 `index.html`，在 `<script>` 區段中的 `questionBank` 編輯區修改題目。每題包含：

- `kind`：內容類型
- `goal`：這題的內容目標
- `ask`：題目要學生判斷的問題，可留空使用預設問題
- `scenario`：題目情境
- `a`、`b`：兩個開場
- `best`：較適合此目標的選項，填 `a` 或 `b`
- `why`：解析
- `clues`：判斷線索標籤
- `lesson`：補充提醒

目前包含混合練習、旅遊分享、知識教學、故事共鳴、商品推薦、親子生活、美食功能型、美妝／跳操、運動連續紀錄、親子省錢、專業教學與品牌借勢、財稅／保險／房產。題目可比較開場金句，也可比較畫面安排與呈現策略。每回合最多五題；題目出場順序會隨機調整。

## 網站範圍

此版本是初階學習體驗：不會要求學生貼上自己的文案，也不會提供個人化改寫。所有題目與解析都在瀏覽器端執行，不需 API 金鑰或資料庫。
