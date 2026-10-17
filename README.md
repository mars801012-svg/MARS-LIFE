# Mars Life

個人照片、模型、興趣與生活文字網站。

## 第一次發布

開啟儲存庫 Settings → Pages。
Build and deployment → Source 選 Deploy from a branch。
Branch 選 main，資料夾選 / (root)，按 Save。
等待部署完成，Pages 設定頁會顯示實際網站網址。
預期網址：https://mars801012-svg.github.io/MARS-LIFE/

## 修改文字與興趣

開啟 index.html → 點鉛筆編輯，搜尋想更改的文字，修改後按 Commit changes。Pages 啟用後會自動更新。
也可以在 ChatGPT 使用 GitHub 外掛，提供要更新的文字及檔案。

## 加入照片

在 GitHub 選 Add file → Upload files，將照片放在 images 資料夾（可拖曳整個資料夾）。建議檔名 model-01.jpg，避免空白。
在 index.html 將照片位置改為：

```html
<div class="photo"><img src="images/model-01.jpg" alt="我的模型作品" loading="lazy"></div>
```

相片建議先縮圖壓縮，單張約 500KB～1MB。

## 編輯方式

這是靜態網站，編輯連結會前往 GitHub，需以擁有寫入權限的帳號登入後儲存。網站本身沒有上傳後台。訪客無法透過網站修改內容。公開儲存庫內的照片與文字都可被瀏覽。
