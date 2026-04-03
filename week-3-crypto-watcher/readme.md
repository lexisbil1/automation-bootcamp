# 🚀 Crypto Watcher – Real-Time Alert System

![Automation](https://img.shields.io/badge/Automation-NoCode-blue)
![Make](https://img.shields.io/badge/Tool-Make.com-purple)
![API](https://img.shields.io/badge/API-CoinGecko-green)

A real-time cryptocurrency monitoring and alert system built using **Make.com**, **CoinGecko API**, **Google Sheets**, and **Lovable UI**.

This system tracks live crypto market data, applies intelligent filtering logic, sends alerts across multiple channels, and visualizes data on a live dashboard.

---

## 📌 Overview

Crypto markets are highly volatile, and monitoring price movements manually can be inefficient.

This system automates the process by:

- Fetching live crypto data
- Applying threshold-based logic
- Sending real-time alerts
- Logging data for historical tracking
- Visualizing insights on a dashboard

---

## 🏗️ System Architecture


Webhook → Make.com → CoinGecko API → Iterator → Filter Logic
→ Email Alerts
→ Telegram Alerts
→ Google Sheets (Data Storage)
→ Lovable UI (Dashboard)


---

## ⚙️ Features

### 🔹 Webhook Trigger
- Initiates the workflow automatically

### 🔹 Crypto Data Retrieval
- Fetches live data from CoinGecko API
- Includes:
  - Price (USD)
  - 24h % change
  - Market cap
  - Trading volume
  - Timestamp

### 🔹 Logic & Filtering
- Detects significant market movements:
  - Greater than +5%
  - Less than -5%

### 🔹 Multi-Channel Alerts
- 📧 Email notifications
- 📲 Telegram alerts

### 🔹 Data Logging
- Stores data in Google Sheets
- Enables historical tracking and analysis

### 🔹 Dashboard (Lovable UI)
- Real-time visualization
- Market overview (gainers, losers, total market cap)
- Clean and responsive interface

---

## 🧰 Tech Stack

- **Make.com** – Automation workflow engine  
- **CoinGecko API** – Crypto market data  
- **Google Sheets** – Data storage & logging  
- **Telegram Bot** – Real-time alerts  
- **Lovable** – Frontend dashboard  

---

## 📊 Sample Output

### Telegram Alert

🚨 Crypto Alert!

Coin: Solana
Price: $79.91
Change: -7.68%
Market Cap: $45B
Time: 2026-04-03


---

## 🎥 Demo

Watch the full walkthrough here:  
👉 https://www.youtube.com/watch?v=QGUzCWvCwB8

---

## 🧪 Testing

The system was tested to ensure:

- ✅ Webhook triggers successfully  
- ✅ API data is retrieved correctly  
- ✅ Filtering logic works as expected  
- ✅ Alerts are delivered via email and Telegram  
- ✅ Data is logged accurately in Google Sheets  
- ✅ Dashboard reflects real-time updates  

---

## 🚀 Future Improvements

- Slack or SMS alerts  
- Advanced analytics dashboard  
- Portfolio tracking  
- Historical trend charts  
- AI-based price prediction  

---

## 🧠 Key Learnings

- API integration and data handling  
- Event-driven automation design  
- Multi-channel notification systems  
- Data visualization workflows  
- End-to-end system architecture  

---

## 👨‍💻 Author

**Alex Agyei**  
Building real-world systems in automation, cybersecurity, and cloud engineering.

📺 YouTube: *The Cyber Path with Alex*
