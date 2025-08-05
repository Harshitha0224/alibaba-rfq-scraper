# Alibaba RFQ Scraper 🔍

This project uses Python and Selenium to scrape RFQ (Request For Quote) listings from Alibaba and export them to a structured CSV.

## Features

- Scrapes RFQs from multiple pages
- Extracts title, quantity, unit, location, date, and buyer name
- Cleans raw data into structured format
- Outputs a final `rfq_output_cleaned.csv` file

## Files

- `alibaba_rfq_scraper_selenium.py`: Scrapes raw RFQ data
- `clean_rfq_output_v2.py`: Cleans and structures scraped data
- `rfq_output_cleaned.csv`: Final result
