# 🖐️ Hand Exercise - MediaPipe 專案

這是一個使用 **Anaconda** 與 **MediaPipe** 實作的手勢辨識協作專案。

---

## 🛠️ 環境快速安裝 (組員必看)

為了避免 **SSL 憑證錯誤** 以及環境衝突，請依照以下步驟操作：

### 1. 基礎設定
打開 **Anaconda Prompt**，先關閉 SSL 驗證並進入你的專案資料夾：
* `conda config --set ssl_verify false`
* `cd [你的專案路徑]`

### 2. 建立環境
使用專案內附的設定檔自動安裝所有套件：
* `conda env create -f environment.yml`

### 3. 啟動環境
* `conda activate mp_env`

---

## 💻 開發流程建議

### 🔹 如何在 VS Code 開發？
1. 開啟資料夾後，按 `Ctrl + Shift + P`。
2. 搜尋 **Python: Select Interpreter**。
3. 選擇帶有 `('mp_env': conda)` 字樣的選項。

### 🔹 如何同步程式碼？
* **下載最新版**：點擊左側「原始檔控制」選單中的 **Pull**。
* **上傳我的修改**：
  1. 寫下 Commit 訊息（例如：`fix: 修改手勢判定閾值`）。
  2. 點擊 **Commit** 然後 **Push**。

---

## ⚠️ 注意事項
* ❌ **不要開啟 VPN**：下載 MediaPipe 模型時開啟 VPN 會導致連線失敗。
* 📁 **不要上傳影片檔**：請確保影片或大圖已加入 `.gitignore`，避免 GitHub 爆掉。
