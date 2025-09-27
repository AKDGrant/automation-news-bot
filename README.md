# Automation News Bot

This project automatically fetches the latest tech headlines using an RSS feed and summarizes them using an AI model. The summarized news is saved into a text report for easy viewing.

---

## Features
- Fetches top headlines from **Hacker News RSS**.
- Uses AI to **summarize each headline** into a simpler, readable sentence.
- Saves everything into a `.txt` file for sharing or reference.

---

## Screenshots

### 1. Fetching Headlines and Model Setup
This shows the code for fetching the RSS feed and setting up the AI model.  
![News Bot Code](automation-news-bot/screenshots/News1.png)

---

### 2. Final Output
This shows the summarized news report that gets saved into a `.txt` file.  
![News Bot Output](automation-news-bot/screenshots/News2.png)

---

## How It Works
1. **Fetch Headlines** – Pulls the top 5 headlines from Hacker News RSS feed.  
2. **Summarize Headlines** – Each headline is summarized using the `flan-t5-base` AI model.  
3. **Save Report** – Summaries are saved to `daily_news_report.txt`.

---

## Tech Stack
- **Python**
- **Transformers (Hugging Face)**
- **Feedparser**
- **Colab**
