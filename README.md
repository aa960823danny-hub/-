# Brown Bear Rhoticity Pronunciation Website

這是一個適合上傳到 GitHub Pages 的單頁互動式網站，用來整理《Brown Bear》中含有字母 **r** 的單字，並比較：

- 英式英語 Received Pronunciation, RP
- 美式英語 General American, GA
- Rhoticity / Non-rhoticity 的語音差異
- 左邊英腔、右邊美腔的發音按鈕

## Files

- `index.html`：網站主檔案，GitHub Pages 會自動讀取這個檔案。

## How to upload to GitHub Pages

1. 在 GitHub 建立一個新的 repository。
2. 把這個資料夾裡的 `index.html` 和 `README.md` 上傳到 repository。
3. 到 repository 的 **Settings**。
4. 點左側 **Pages**。
5. 在 **Build and deployment** 選擇：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. 儲存後等 1–3 分鐘，GitHub 會產生一個公開網址。

## Note

發音按鈕使用瀏覽器內建的 Web Speech API。不同裝置或瀏覽器的英腔/美腔語音庫可能略有差異，建議使用 Chrome 或 Edge 開啟。
