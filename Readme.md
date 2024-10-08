# Taipei Hotpot Map Project

## Project Overview
This project aims to create a web-based database system for hotpot restaurants in Taipei. Users can search for and locate hotpot restaurants using various criteria, while administrators can manage the database content.
## System Architecture
* Front-end: HTML, CSS
* Back-end: Python (Flask)
* Database: SQLite

## Data Source
Restaurant data is collected from the Google Maps API, including name, rating, dining options, address, coordinates, business hours, and reviews.
  
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

## Project Structure

* [documents/Scraper](./documents/Scraper): Google Maps data scraping scripts
* [documents/json2sql](./documents/json2sql): Database schema construction and data import scripts
* [codes](./codes): Web frontend and backend code

## Setup and Usage
1. Clone the repository
2. Run the application:
```
$ cd codes/final && python main.py
```
Open a web browser and navigate to http://localhost:5000

### **Result**

**Home Page**
<img src="./figure/main.jpg" width = "1000" height = "500" div align=center />


**Searching Result**
<img src="./figure/query.png" width = "1000" height = "700" div align=center />


**Map Display**
<img src="./figure/map.jpg" width = "1000" height = "600" div align=center />

