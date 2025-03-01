# Rightmove Property Scraper

A web scraping tool built using **Scrapy** to extract property price data from the Rightmove website. This scraper navigates through paginated results and collects essential property information, including address, property type, transaction history, location, and the detail URL.

## 📖 Project Description

The **Rightmove Property Scraper** is designed to gather structured data on property sales from the Rightmove house prices section. It scrapes data from multiple pages automatically and outputs key details in JSON or other exportable formats. This tool is ideal for data analysis, market research, or integration with real estate data pipelines.

### ✨ Key Features

- **Automated Page Navigation:** Scrapes data across all available pages.
- **Property Details Extraction:** Collects address, type, transactions, location, and detail URL.
- **JSON Data Output:** Stores data in a structured format, easy for analysis or integration.
- **Scalable & Extendable:** Built on Scrapy, allowing for easy adaptation to other real estate sites.

### 🚀 How It Works

1. **Initialization:** The scraper starts at a specified URL on the Rightmove site.
2. **Data Extraction:** It extracts data from dynamically loaded JavaScript using XPath.
3. **Pagination Handling:** Automatically moves to the next page until no more data is available.
4. **Data Output:** Returns scraped data in a structured JSON format.

### 🔧 Installation

```bash
git clone https://github.com/yourusername/Rightmove-Property-Scraper.git
cd Rightmove-Property-Scraper
pip install -r requirements.txt
