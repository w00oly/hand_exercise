#Hand Exercise - MediaPipe 專案
這是一個使用 Anaconda 環境與 MediaPipe 實作的手勢辨識專案。

🚀 環境安裝指南 (組員必看)
由於部分網路環境（如學校 VPN 或防火牆）可能會導致 SSL 憑證錯誤，請務必按照以下步驟建立環境：

1. 下裝並解壓縮專案
從 GitHub 下載本專案後，請開啟 Anaconda Prompt 並進入該資料夾。

2. 處理 SSL 驗證問題
在安裝套件前，請先執行此指令以避開憑證報錯：

Bash
conda config --set ssl_verify false
3. 根據設定檔建立環境
執行以下指令，系統會自動安裝 Python 3.10、MediaPipe 以及 OpenCV：

Bash
conda env create -f environment.yml
4. 啟動環境
Bash
conda activate mp_env
💻 開發說明
如何執行程式
使用 VS Code 開啟專案資料夾。

按下 Ctrl + Shift + P 選擇解譯器 (Select Interpreter)，選取 ('mp_env': conda)。

執行 main.py (或其他開發中的檔案)。

協作注意事項
不要開啟 VPN：安裝套件與第一次執行 MediaPipe 模型下載時，請關閉學校 VPN。

更新環境：如果有人新增了新套件，請記得更新 environment.yml 並推送到 GitHub。
