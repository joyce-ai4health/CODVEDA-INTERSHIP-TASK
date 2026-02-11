# NODVEDA-INTERSHIP-TASK
# Level 1 – Task 1: Data Collection and Web Scraping

## Project Overview
This project focuses on collecting data from a publicly available website using web scraping techniques. 
The goal is to extract meaningful information, store it in a structured format, and prepare it for further analysis.

## Website Used
- Website: https://books.toscrape.com/
- Description: A sandbox website created for practicing web scraping.

## Data Collected
The following information was scraped from the website:
- Book Title
- Book Price

The data was collected from multiple pages using pagination.

## Tools and Libraries Used
- Python
- requests – to send HTTP requests and fetch webpage content
- BeautifulSoup – to parse HTML and extract data
- pandas – to structure the data and save it as a CSV file
- time – to add delays between requests

## Steps Followed
1. Sent an HTTP request to fetch the webpage content.
2. Parsed the HTML structure using BeautifulSoup.
3. Identified book containers using HTML tags and class names.
4. Extracted book titles and prices.
5. Handled pagination to scrape data from multiple pages.
6. Stored the collected data in a pandas DataFrame.
7. Saved the final dataset as a CSV file.

## Output
- File: `books_all_pages.csv`
- Format: CSV
- Description: Contains book titles and prices scraped from multiple pages.

## Conclusion
This task demonstrates the ability to collect data from a website, handle pagination, and store the data in a structured format suitable for analysis.
