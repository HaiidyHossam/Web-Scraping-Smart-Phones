
# Web Scraping Assessment — MobileMasr & Dubizzle

## Overview
This Python notebook scrapes used smartphone listings from:
- **MobileMasr**  
- **Dubizzle Egypt**

The script collects:
- Product Name  
- Price  
- Seller / Title  
- Listing URL  
- Location  

and saves the results to CSV files, then merges them into one dataset.

---

## Tools Used
- **Python 3.x**
- **Selenium** (for dynamic web scraping)
- **Pandas** (for saving and merging data)
- **Chrome WebDriver** 

---

## How to Run
1. Install dependencies:
   pip install selenium pandas
2. Open the Jupyter notebook file.
3. Run all cells **sequentially from top to bottom**.
   The script will:

   * Scrape data from MobileMasr
   * Scrape data from Dubizzle
   * Save both results to CSV
   * Merge them into one final CSV file:


     assessment_merged_mobilemasr_dubizzle.csv
    



## Notes

* The script handles pagination automatically.
* Basic error handling is included to skip broken listings.


