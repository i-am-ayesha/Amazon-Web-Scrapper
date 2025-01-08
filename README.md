# 🛍️ Amazon Price Tracker 🕵️‍♂️

## 📋 Project Overview
Amazon Price Tracker is a Python-based web scraper that monitors the price of an Amazon product over time and logs the data in a CSV file. You can set it up to send an email notification when the price drops below a specified threshold. The script runs daily to help you catch the best deals!

## ✨ Features
#### 🔍 Track Prices Automatically: 
Scrapes real-time price and product details from Amazon.
#### 📊 Daily Price Updates: 
Appends the product price, title, and the current date to a CSV file.
#### 📬 Email Notifications: 
Sends an alert email when the price drops below your desired amount.
#### 🛠️ Customizable: 
Easily change the product URL or price threshold.
#### 🔁 Automated Scheduling: 
The script runs daily and logs data every 24 hours.

## ⚙️ How It Works
#### 1. Web Scraping with BeautifulSoup: 
The script fetches the Amazon product page using requests and scrapes the title and price using BeautifulSoup.
#### 2. Data Storage:
The scraped data is cleaned and stored in a CSV file with columns for the product title, price, and date.
#### 3. Email Notifications: 
If the price drops below your target, the script sends an email alert.
#### 4. Daily Checks: 
The script runs continuously, checking the price every 24 hours.
