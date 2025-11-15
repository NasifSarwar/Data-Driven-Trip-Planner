# 🏨 Web Scraping & Data Analysis of Berlin Hotel Listings  
*Booking.com · Kayak · Agoda · Python · Selenium*

This repository contains a full end-to-end mini-project where I:

- Scrape **hotel and apartment listings in Berlin** from  
  **Agoda, Booking.com, and Kayak** for a fixed 3-night stay  
  (31/12/2025 → 03/01/2026).
- Clean and standardize the scraped data.
- Combine all platforms into **one unified dataset**.
- Perform **exploratory data analysis (EDA)** and visualizations.
- Build an **interactive console “Accommodation Finder”** on top of the data.

Everything is implemented in the Jupyter notebook:  
`Data_Science_Lab_1.ipynb`.

---

## 🎯 Project Goals

1. Practice **web scraping** on real, dynamic, JavaScript-heavy booking websites.
2. Learn how to **avoid basic bot detection** using Selenium options and “stealth” tricks.
3. Turn messy scraped HTML into a **clean, tabular dataset** ready for analysis.
4. Compare offers from **multiple platforms** in a single combined DataFrame.
5. Build a small, **user-friendly accommodation search tool** in pure Python.

---

## 🗂 Data Sources & Scope

The notebook focuses on **Berlin** as the destination and a **3-night stay**:

- **Agoda** – hotels in Berlin  
- **Booking.com** – mainly apartments in Berlin  
- **Kayak** – hotel results in Berlin  

For each listing, the goal is to collect (as available):

- `name`
- `address`
- `stars`
- `rating`
- `number of ratings`
- `total price ($)` (for 3 nights)
- `price per night ($)`
- `distance from center / city centre`
- `description`
- `images` / `photo_urls`
- `source` (Booking / Kayak / Agoda) – in the combined dataset

---

## 🔧 Main Components of the Notebook

### 0. Environment & Library Setup

The notebook shows how to set up everything (especially for Google Colab):

- Install and configure:
  - `selenium`
  - `webdriver-manager`
  - `selenium-stealth` (or similar stealth options)
  - `beautifulsoup4`
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
- Install and configure **Google Chrome** and **ChromeDriver**.
- Configure **Chrome options** to reduce detection:
  - Custom `user-agent`
  - Disable automation flags
  - Headless mode, window size, etc.


