# Crunchbase Scraper

---

## Overview
This project is a Python-based web scraping tool designed to automate the extraction of company data from Crunchbase, using the Selenium library, the script navigates through Crunchbase pages, logs in, and retrieves detailed company information, including location, employee count, funding details, and website links.
---

## Features
- **Automated Login**: Logs into Crunchbase using the provided credentials.
- **Dynamic Web Scraping**: Iterates through a list of Crunchbase company URLs to extract company funding information.
- **Randomized Delays**: Mimics human behavior during execution.
- **Error Handling**: Ensures smooth execution even when some data fields are missing or inaccessible.
- **Data Export**: Saves the scraped data into an Excel file, merging it with the original input data for completeness.

---

## Data Extracted
For each company, the following information is collected:
- **Basic Information**:
  - Company Name
  - Location
  - Number of Employees
  - Website URL
- **Financial Information**:
  - Total Funding
  - Number of Funding Rounds
  - Seed Funding Details
  - Date of Last Funding
  - Amount Raised in Last Round
  - Year of Last Round

---

## Requirements
To run this script, you need the following:
1. **Python 3.8+**
2. **Dependencies**:
   - `selenium`: For web automation.
   - `pandas`: For data processing.
   - `chromedriver`: Compatible version for your Chrome browser.
3. **Input File**:
   - An Excel file with URLs of company profiles to scrape.

---

## Setup and Usage
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
2. **Install Dependencies**:
   ```bash
   pip install selenium pandas
3. **Prepare the Input File**:
   - Place the input excel file containing the valid Crunchbase URLs in the working directory
4. **Run the Script**:
   ```bash
   python crunchbase_scraper.ipynb
5. **Output**:
   - The scraped date is saved in the working directory

---



   
