# Wikipedia US Companies Revenue Scraper

This Jupyter Notebook scrapes a table from the Wikipedia page  
[List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)  
using `requests` and `BeautifulSoup`. The scraped data is processed into a pandas DataFrame and saved as a custom CSV file.

---

## 📌 What It Does

- Sends a GET request to the Wikipedia page
- Uses BeautifulSoup to locate and parse the first HTML table
- Extracts table headers and row data manually
- Stores the cleaned data in a pandas DataFrame
- Saves the result as `Wikipedia_Scraping_output.csv` locally

---

## 🧰 Technologies Used

- Python 3
- Jupyter Notebook
- `requests`
- `beautifulsoup4`
- `pandas`
