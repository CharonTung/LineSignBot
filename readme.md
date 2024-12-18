# LINE 群組簽到機器人 (Sign BOT)

使用Google App Script作為WebAPI，搭配Line BOT 實現球隊訓練簽到、簽退等功能，並且自動統計訓練內容、時數、時間。

## 功能 Features

- 自動統計訓練時間
- 隨時查看球室使用狀況
- 紀錄訓練內容
- 視覺化統整網頁，可篩選用戶、時間

## Demo

<img src="https://github.com/CharonTung/LineSignBot/blob/main/demo1.jpg" width="300px">
<img src="https://github.com/CharonTung/LineSignBot/blob/main/demo2.jpg" width="300px">
<img src="https://github.com/CharonTung/LineSignBot/blob/main/demo3.png" width="300px">

## 快速開始

### 需求

- Googlge sheet、App script
- Line Developers

### 安裝

1. 創立Line Developers帳號，並取得Token

2. 建立Google App Script

3. 建立Google Sheet 一張作為暫存資料表，另一張則為記錄資料表

4. 在Google App Script 建立專案並且複製main.gs、api.gs至GAS

5. 配置環境變量:

   ```bash
   CHANNEL_ACCESS_TOKEN = 'your_token'
   sheet = SpreadsheetApp.openById('your_sheet_id')
   sheetTemp = SpreadsheetApp.openById('your_temp_sheet_id')

7. 將相對應Webhook填入Line BOT

8. 配置view.html的webAPI網址

## 貢獻

1. Fork 本倉庫。
2. 創建你的功能分支：`git checkout -b feature-name`。
3. 提交變更：`git commit -m 'Add feature'`。
4. 推送到分支：`git push origin feature-name`。
5. 發送 Pull Request。

## 授權

本項目基於 MIT 許可證進行授權。
