# Brown Bear Rhoticity Pronunciation Website

這是一個可直接上傳到 GitHub Pages 的單頁互動式網站。

## 內容特色

- 《Brown Bear》中含有 r 的單字整理
- 英式英語 RP vs. 美式英語 GA 音標比較
- 每個單字都有發音按鈕
  - 左邊：英腔 UK / RP
  - 右邊：美腔 US / GA
- 新增參考資源區
- 移除「報告結論」區域
- 音標參照 Cambridge Dictionary 的 pronunciation 頁面

## GitHub Pages 上傳方式

1. 建立一個 GitHub repository。
2. 將本資料夾中的 `index.html`、`README.md`、`.nojekyll` 上傳到 repository 根目錄。
3. 進入 repository 的 `Settings`。
4. 點選 `Pages`。
5. Source 選 `Deploy from a branch`。
6. Branch 選 `main`，Folder 選 `/root`。
7. 儲存後等待幾分鐘，就會得到網站連結。

## 注意

發音按鈕使用瀏覽器內建 Web Speech API。不同裝置可用的英腔／美腔語音庫可能不同，建議使用 Chrome 或 Edge。
