# 🛒 Product Price Comparison Script (Amazon & Flipkart)

This Python script allows you to search for a product and automatically compare its price on **Amazon** and **Flipkart**, two of India's largest e-commerce platforms.

It uses `requests` and `BeautifulSoup` to scrape and parse product names and prices from both websites and provides direct URLs to the listings with the lowest price.

---

## 📌 Features

* Searches for a product on Amazon and Flipkart.
* Extracts product names and prices.
* Compares prices and identifies the lowest one.
* Provides direct URLs to the product listings.
* Simple and easy-to-run in the terminal.

---

## 🛠 Requirements

Make sure you have Python 3 installed, along with the required libraries:

```bash
pip install requests beautifulsoup4
```

---

## 🚀 Usage

1. Clone this repository or download the script.
2. Run the script in your terminal:

```bash
python compare_prices.py
```

3. Enter the product name when prompted.

Example:

```bash
Product Name:
iPhone 14
```

The script will output:

* Product names and prices from Amazon and Flipkart.
* The minimum available price.
* Direct links to each product page.

---

## ⚠️ Note

* This script uses simple scraping methods and may break if Amazon or Flipkart changes their website structure.
* Amazon frequently blocks automated scripts. If you face issues, try adding proxy support or using a rotating user-agent list.
* This script is intended for educational and personal use only. Use responsibly and avoid overloading e-commerce sites.

---
## 👨‍💻 Author

Developed by **Abhilash**

---
