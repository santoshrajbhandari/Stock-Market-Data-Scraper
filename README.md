# Stock-Market-Data-Scraper
## Overview
This project is a web scraper that extracts live Nepse(Nepal Stock Exchange) data from merolagani.com using Selenium and BeautifulSoup. The extracted data is saved as a CSV file for further analysis.
## Features
- Scrapes live stock market data dynamically.
- Handles JavaScript-rendered content using Selenium.
- Saves extracted data as a CSV file.
- Works in headless mode(runs in the background without opening a browser).
## Installation
### Install Dependencies
Make sure you have Python installed. Then, install the required packages:

```pip install -r requirements.txt```

### Set Up WebDriver
Download the Edge WebDriver from [Microsoft Edge Driver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/?form=MA13LH) and place it in the appropriate directory.
## Usage
Run the cell to scrape stock market data and save it as a CSV file. The csv file will be saved to current directory.
## Automating with Task Scheduler (Windows)
- Open Task Scheduler.
- Click Create Basic Task.
- Set Trigger (e.g., every hour).
- Set Action → Start a Program.
- Browse and select python.exe, then add main.py as an argument.
## Author
Santosh Kumar Rajbhandari
