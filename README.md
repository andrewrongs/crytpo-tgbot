<div align="center">

# 加密貨幣簡易查詢機器人
![Static Badge](https://img.shields.io/badge/Node-v18.20.2-blue) 

</div>

## 資料夾結構
 - assets # 圖片放置處
  - src # 靜態資源放置處
    - bot # 機器人指令放置處
    - lib # 靜態資源
- index.js 指令入口檔
## 專案建置
---
```
npm i
```
---
## 配置
-  BotFather 設定以下指令 
    - start
    - price
    - plate
    - k
-  複製 bot.example 成 bot.js
-  填入 apiKey

## 專案功能概述
#### 1. 啟用機器人
```
/start
```

![/start](assets/image5.png)

#### 2. 查詢價格 ＆ 市值
```
/price
```
![/price](assets/image4.png)

```
/price top
```
![/price](assets/image3.png)

#### 3. 查詢k線圖 xxx為要搜尋幣種
```
/k XXX
```
![/price](assets/image1.png)

#### 4. 查詢分類板塊幣種
```
/plate
```
![/price](assets/image2.png)

## 指令
輸入指令即可啟動Bot
```
node index.js
```
