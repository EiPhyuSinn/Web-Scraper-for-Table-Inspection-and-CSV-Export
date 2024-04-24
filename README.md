# Web Scraper for Table Inspection and CSV Export

This Jupyter Notebook project provides a web scraping tool that inspects tables on a website and exports the data to a CSV file on your local computer.

## Overview

The web scraper is designed to:

- Access a specific webpage containing tables.
- Parse the HTML to identify tables and extract their contents.
- Convert the table data into a structured format.
- Export the data to a CSV file for further analysis or storage.

## Notebook Contents

- **webscraper.ipynb**: Jupyter Notebook containing the Python code for the web scraping tool.

## Getting Started

To use the web scraper:

1. Clone or download this repository to your local machine.
2. Open the `webscraper.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Follow the instructions provided in the notebook to:
   - Specify the URL of the webpage to scrape.
   - Inspect and select the tables you want to extract data from.
   - Run the code cells to execute the scraping process.
4. Once the scraping is complete, the notebook will generate a CSV file containing the extracted data in the same directory as the notebook.

## Dependencies

This project requires the following Python libraries:

- `requests`: For making HTTP requests to fetch webpage content.
- `BeautifulSoup`: For parsing HTML content and extracting data from web pages.
- `pandas`: For data manipulation and exporting data to CSV format.

You can install these dependencies using pip:

