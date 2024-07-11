# scrape_adebooks
This project consists of three web scraping scripts that extract data from AbeBooks and other websites. Each script is designed to handle different tasks: extracting book information, finding specific URLs, and identifying prices within certain ranges. The data is processed and saved into various output files for further analysis.

# Web Scraping Project for AbeBooks and Other Websites

This project contains three distinct scripts designed for web scraping data from AbeBooks and other websites. Each script performs a specific function: extracting book information, finding specific URLs, and identifying prices within certain ranges.

## Description

### First Project
The first script scrapes detailed information about books listed on AbeBooks, including title, author, ISBN-13, price, publisher, publication year, binding, and image link. The data is saved in a TSV file.

### Second Project
The second script scrapes product URLs from a specified range of lines in a text file containing URLs. It identifies URLs with certain delivery conditions and saves them to a file.

### Third Project
The third script checks the prices of books listed on AbeBooks, identifying those within specific price ranges (four-digit, five-digit, etc.). The results are saved into separate files based on the price ranges.

## Requirements
- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `tqdm` library
- `pandas` library
- `re` module (standard library)
- `time` module (standard library)
