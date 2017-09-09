# hackathon-ChatBot

### 安裝 slack 套件 slackbot
pip install slackbot

### 安裝聊天機器人引擎 chatterbot
https://github.com/gunthercox/ChatterBot \
pip install chatterbot

### 訓練文件資料夾
windows參考路徑：C:\Users\arioscen\Anaconda3\Lib\site-packages\chatterbot_corpus\data\chinese\ \
將整理為 yml 的問答資料檔放入(若原始檔為 JSON 格式，用套件或工具轉檔) \
語法 chatbot.train("chatterbot.corpus.chinese") 會將 chinese 資料夾下所有的 yml 檔案載入

### 注意事項
注意資料前處理，chatterbot 套件內有提供相關語法 \
訓練後的資料會存放在 sqlite 資料庫(自動產生在同資料夾下) \
資料筆數需要控制在約 1000筆內，避免反應時間過長

### 同隊小夥伴的github
https://github.com/keeivan1007/chat_bot