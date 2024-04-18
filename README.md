# Companies-Data-Scraping
# CompanyReviewScraper

## Overview:
CompanyReviewScraper is a web scraping project designed to extract company reviews, including company names, ratings, and reviews from various websites. The scraped data is then stored in CSV files for further analysis and insights.

## Features:
- **Data Extraction**: Scrapes company reviews from specified websites.
- **Data Storage**: Saves scraped data in CSV files for easy access and analysis.
- **Customization**: Allows customization of scraping parameters such as target websites and review categories.
- **Error Handling**: Includes error handling mechanisms to manage unexpected issues during scraping.

## Installation:
1. Clone the repository: git clone https://github.com/yourusername/CompanyReviewScraper.git
2. Install dependencies: pip install -r requirements.txt

## Usage:
1. Modify the configuration file (`config.json`) to specify target websites and scraping parameters.
2. Run the scraper script: python scraper.py

3. The scraped data will be saved in CSV files in the specified output directory.

## Configuration:
- **config.json**: Contains configuration settings such as target URLs, scraping parameters, and output directory.

## Dependencies:
- BeautifulSoup
- Requests
- Pandas

