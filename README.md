# Homework 07: Web Scraping

This assignment includes four parts using Python to scrape data from websites and save it as CSV files.

---

## Part One: U.S. Presidents  
- Scraped from Wikipedia using `pandas.read_html()`  
- Cleaned up column names  
- Combined party columns  
- Saved as `us_presidents.csv`

---

## Part Two: Le Monde Articles  
- Scraped articles from https://www.lemonde.fr using `requests` and `BeautifulSoup`  
- Collected title, subhead, URL, premium status, byline, article type, and image  
- Handled missing or incomplete fields  
- Saved as `lemonde_articles.csv`

---

## Part Three: Arizona License Locations  
- Scraped table from https://travel-id-documents.az.gov  
- Used `headers` in `requests.get()`  
- Parsed name, address, phone, hours, and links  
- Saved as `az_license_locations.csv`

---

## Part Four: TN Bankruptcy Court Search  
- Searched for "CAR" and scraped results  
- Collected case name, PDF link, category, and extra details  
- Split details into separate columns  
- Saved as `car_case_results.csv`

---

## Tools Used  
- Python  
- `pandas`  
- `requests`  
- `BeautifulSoup`

