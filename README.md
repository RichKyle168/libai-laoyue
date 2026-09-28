# libai-laoyue
李白撈月

月夜江上泛舟撈月的手機 3D 小遊戲（three.js）。撈到幾輪月亮，李白便吟出含那個數字的詩句；終局呈現「舉杯邀明月，對影成三人」。

- 整個遊戲就是 `index.html` 一個檔案，吟誦聲音已內建。
- three.js 從 jsDelivr CDN 載入，字體用 Google Fonts，所以玩的時候需要連網。

## 部署到 Render

New → Static Site → 選這個 repo

- Build Command：留空
- Publish Directory：`.`

之後每次推到 `main`，Render 都會自動重新部署。
