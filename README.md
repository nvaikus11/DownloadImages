# 🖼️ Google Image Downloader with Selenium

This Python script allows you to **search for images on Google** based on a user-provided keyword and **automatically download up to 200 images** into a local folder using **Selenium** and **web scraping techniques**.

---

## 🚀 Features

- 🔍 Prompt-based keyword entry for flexible searches
- 🤖 Human-like scrolling to load more images
- 🧠 Smart image URL extraction (`src`, `data-src`, `data-iurl`)
- 🛡️ Custom user-agent to avoid detection by Google
- 📁 Automatically creates organized folders for each keyword
- 💡 Error handling for missing images and download failures

---

## 📦 Requirements

Install Python dependencies with:

```bash
pip install selenium webdriver-manager
