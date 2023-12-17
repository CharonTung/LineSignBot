LINE 群組簽到機器人 (Sign BOT)
====  
使用Google App Script作為WebAPI，搭配Line BOT 實現球隊訓練簽到、簽退等功能，並且自動統計訓練內容、時數、時間。

動機 Motivation
------
球隊每次訓練結束都要填寫表單，非常麻煩，因此直接把這份工作結合到人人都有的Line進行，節省時間，方便資料統計。

功能 Features
------
* 一進一出，防止重複進入
* 自動統計訓練時間
* 隨時查看球室使用狀況
* 使用Google App Script及Google Sheet，無須架設任何伺服器

實際使用 Demo
-----
<img src="https://github.com/CharonTung/LineSignBot/blob/main/demo1.jpg" width="300px">
<img src="https://github.com/CharonTung/LineSignBot/blob/main/demo2.jpg" width="300px">

使用方法 How to Use
-----
#### 1.創立Line Developers帳號，並取得Token
#### 2.建立Google App Script
#### 3.建立Google Sheet 一張作為暫存資料表，另一張則為記錄資料表
#### 4.在Google App Script 建立專案並且複製main.gs至GAS
#### 5.依照順序填入Token、SheetID、TempSheetID並部屬網路應用程式
#### 6.將相對應Webhook填入Line BOT
#### 7.享用成果


License
-----
MIT License 歡迎自行運用此份專案於商業與個人用途，如果你願意標記我為出處的話，將對我是莫大的鼓勵，感謝！ Feel free to fork this project and use it for your own work. However, it would be great if you credit me.
