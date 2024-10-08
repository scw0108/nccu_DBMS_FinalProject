# Taipei Hotpot Map Project

## Project Overview
This project aims to create a web-based database system for hotpot restaurants in Taipei. Users can search for and locate hotpot restaurants using various criteria, while administrators can manage the database content.
## System Architecture
* Front-end: HTML, CSS
* Back-end: Python (Flask)
* Database: SQLite
  
![Architecture](https://github.com/user-attachments/assets/68f5820a-4a74-42e2-aae3-9aad59b0e676)

## ER Model
![ER_MODEL](https://github.com/user-attachments/assets/3ac76f37-96d5-4dd9-81c3-dc057b8317d6)

## Features

### User Features:

* Search for restaurants based on area, time, and price
* View restaurant information (name, price level, average rating, business hours)
* See detailed restaurant information and reviews
* Filter restaurants by current operating hours
* Sort restaurants by average rating or price level
* View restaurant locations on Google Maps

### Admin Features:

* Add new restaurant information
* Update existing restaurant information (review count and average rating)
* Delete restaurant information (for closed businesses)




## 描述
- 從Google爬取的資料放在documents/Scarper。</br>
- 建構火鍋Schema和將Google爬取的資料匯入到database裡的程式碼放在documents/json2sql。</br>
- 網頁前端程式碼放在codes。</br>

## 示範
網頁內容請直接跑在codes/final底下的main.py

### **執行方式** 
```
cd codes/final
python main.py
```
### **執行結果**

**主頁面**
<img src="./figure/main.jpg" width = "1000" height = "500" div align=center />


**搜尋結果**
<img src="./figure/query.png" width = "1000" height = "700" div align=center />


**地圖顯示**
<img src="./figure/map.jpg" width = "1000" height = "600" div align=center />

