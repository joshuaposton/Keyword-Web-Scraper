# Web Scraper for Keyword Detection

This Python script is designed to crawl through a website, recursively scraping pages for specific keywords, and saving the URLs and the keywords found to a CSV file. The script is configured to limit the depth of crawling to avoid overloading the system with too many pages.

## Features
- **Recursive Web Scraping**: The script starts from a landing page and follows links to crawl through the entire website.
- **Keyword Detection**: The script checks each page for specific keywords like `survey`, `program assessment`, and `program evaluation`.
- **CSV Export**: Results (URL and the keyword found) are immediately saved to a CSV file for convenience and incremental storage.

## Requirements

To run the script, you need the following Python packages:

- `requests`
- `beautifulsoup4`
- `python-dotenv` (optional, for managing environment variables)

You can install the dependencies using the following command:

```bash
pip install -r requirements.txt
