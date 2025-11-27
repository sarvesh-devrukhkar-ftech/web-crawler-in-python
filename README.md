# 🕷️ BBC Web Crawler (Python)

A simple Python-based web crawler that fetches the BBC homepage, parses the HTML, extracts all valid links, and continues crawling discovered pages.  
This project was built using **requests** and **BeautifulSoup4** as part of internship learning tasks.

---

## 🚀 Features

- Fetches HTML pages using `requests`
- Parses page content using `BeautifulSoup`
- Extracts and normalizes all valid `<a>` links
- Maintains a **frontier** list for crawling
- Uses a **visited** dictionary to prevent repeated crawling
- Basic error handling for network issues
- URL filtering (skips # links, help links, invalid URLs)

---

## 🛠️ Technologies Used

- **Python 3.x**
- **requests**
- **beautifulsoup4**

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/sarvesh-devrukhkar-ftech/web-crawler-in-python.git
cd web-crawler-in-python

# Create a virtual environment
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Run the Crawler
python crawler.py
```