# 🚨 Week 4: Social Media Monitoring & Alerts System

This project is an automated monitoring system that tracks online mentions of keywords, classifies sentiment using rule-based logic, and triggers alerts or stores results accordingly.

---

## 🔍 Features

- ⏱ Runs automatically every 15 minutes
- 🌐 Fetches news articles using NewsAPI
- 🧠 Rule-based sentiment classification
- 🚨 Sends Telegram alerts for negative mentions
- ⭐ Stores positive mentions in Airtable
- 📊 Logs all results in Google Sheets

---

## 🏗 System Architecture

![Architecture](./week-4-social-media-monitoring/screenshots/architecture.png)

---

## 🏗 Workflow Overview

Cron → HTTP Request → Data Processing → Sentiment Analysis → Routing → Alerts & Storage

---

## 🧠 Sentiment Logic

### Negative Keywords
- scam, fraud, breach, hack, issue, fail, leak

### Positive Keywords
- amazing, great, excellent, love, best, secure, fast, success

---

## 📸 Screenshots

(Add screenshots in the screenshots folder)

---

## 🎥 Demo

(Add your demo video link)

---

## 🛠 Tools Used

- n8n
- NewsAPI
- Telegram
- Airtable
- Google Sheets

---

## 🔥 Key Insight

This system mimics a SOC-style monitoring pipeline where events are ingested, analyzed, and escalated automatically.

---

## 👨‍💻 Author

Alex Agyei
