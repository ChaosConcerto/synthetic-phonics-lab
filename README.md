# Synthetic Phonics Lab v0.1

繁體中文互動式 Synthetic Phonics 學習原型，適合成人英語初學者探索音素、字素與拼讀練習。

## 功能

- 六項能力自評
- 字素與 IPA 對應提示
- 合成拼讀練習
- 聽音反向拼寫與答案核對
- 瀏覽器本機學習紀錄與 JSON 匯出

## 限制

- 這是探索性教學原型，不是標準化測驗。
- 語音使用裝置內建英文語音合成；例字音訊不等於獨立音素錄音。
- 不提供語音錄製、發音評分、AI 評分或自適應演算法。
- 紀錄只存於目前瀏覽器的 `localStorage`，不會跨裝置同步。
- 尚未實作間隔複習、延遲保留測驗或陌生假字遷移測驗。

## 本機預覽

直接以瀏覽器開啟 `index.html`。網站不需要建置工具、後端或外部套件。

## GitHub Pages 部署

1. 將此資料夾內容放在 Repository 的 `main` 分支根目錄，確保 `index.html` 位於根目錄。
2. 在 Repository 的 **Settings → Pages** 選擇 **Deploy from a branch**。
3. 選擇 `main` 與 `/(root)`，儲存並等待部署完成。
4. 以 GitHub Pages 顯示的 HTTPS 網址開啟網站。

部署前請先檢查 Repository 內容與可公開資訊，並確認網站功能及語音在目標裝置正常。
