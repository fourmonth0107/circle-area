# 圓面積推導互動教具

這是一個可直接部署到 GitHub Pages 的互動式圓面積教具。

## 功能

- 完整圓觀察
- 圓切割成等分扇形
- 扇形交錯重組
- 調整等分數，觀察圖形逐漸接近長方形
- 找出底約等於 πr
- 找出高等於 r
- 透過選擇題推導圓面積 πr²
- 支援手機、iPad、電腦瀏覽器

## GitHub Pages 部署方式

1. 在 GitHub 建立一個新的 Repository，例如：
   `circle-area`
2. 將本資料夾中的所有檔案上傳到 Repository 根目錄。
3. 進入 Repository：
   `Settings` → `Pages`
4. 在 `Build and deployment`：
   - Source 選擇 `Deploy from a branch`
   - Branch 選擇 `main`
   - Folder 選擇 `/ (root)`
5. 按下 Save。
6. 稍後 GitHub Pages 會提供網址，例如：
   `https://你的帳號.github.io/circle-area/`

## 檔案

- `index.html`：完整教具，不需其他套件。

## 教學建議

建議不要一開始就公布 πr²。

先讓學生：

1. 觀察圓。
2. 將圓切割。
3. 觀察扇形交錯排列。
4. 將等分數從 6 增加到 48。
5. 思考重組圖形像什麼。
6. 判斷「底」與「高」各對應圓的哪個量。
7. 最後才導出 `πr × r = πr²`。
