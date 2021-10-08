# 中文版google meet auto join教學
---
## 從雲端抓檔案
1. 按一下**donwload zip**
![downloadcode](https://i.imgur.com/vcWElDG.png)

1. 解壓縮
**好了已經完成的第一步接著在跟著我來繼續**

## 建置環境
**我們已經下載了源代碼，接下來我們需要一些東西來開啟他(有點像驅動軟體)**
1. 從[nodejs.org](https://nodejs.org/)下載(通常是按左邊的東西)，然後一直按下一步...
![downloadnodejs](https://i.imgur.com/95CDlpq.png)

1. 接下來下載[chromedriver](https://chromedriver.storage.googleapis.com/index.html)到根目錄
補充說明:**根目錄就是解壓後的資料夾**

**好了，接下來就是設定運行專案了**

## 設定專案
1. 運行
```
npm i
```
來下載套件

2. 接下來要客製化我們的內容，請在 ***.env*** 檔案中跟改你的帳號密碼
>gmail=your_gmail
>>password=your_password
>>>googlemeet=meet_code

3. 接下來來我們要下載的東西都下載完了，我們來確認一下

* node_modules 資料夾
* main.js
* .env
* *.gitignore*
* *README.md*
* package-lock.json
* pachage.json
* xpath.json
* *LICENSE*
>斜體字表示可以刪掉(但不建議)

## 運行專案

**使用以下指令來執行**
```
node main.js
```
