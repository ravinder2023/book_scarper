# book_scarper
web scraping
#  Advanced Book Data Web Scraper

This project is a Python-based web scraper that extracts structured book data from the demo website http://books.toscrape.com.

Unlike basic scrapers, this version navigates through multiple listing pages and visits each product’s detail page to collect additional information such as stock availability and category.

---

##  Features

✔ Multi-page scraping  
✔ Extracts detailed book information:
- Title
- Price
- Rating (from CSS classes)
- Stock Availability
- Book Category  
✔ Visits each product page to gather extra metadata  
✔ Stores results in CSV format  
✔ Includes polite request delay to avoid server overload  
✔ Beginner-friendly but follows real-world scraping workflow  

---

## Tech Stack

- Python  
- Requests  
- BeautifulSoup4  
- CSV module  
- Time module (for request throttling)

---

## Project Structure

scraper.ipynb
books.csv
README.md
