# Daraz Data Scraper
This is a Python script that uses Selenium to scrape product information from the Daraz website. The script extracts data about Nokia smartphones listed on the Daraz website. It navigates through multiple pages of Product listings and collects product details such as the title, brand, price, and specifications. The scraped data is then saved into a CSV file.

# Prerequisites
Python: Make sure you have Python installed on your system.
Chrome WebDriver: You need to have the Chrome WebDriver executable (chromedriver.exe) compatible with your Chrome browser version. Download it from the official website: ChromeDriver Downloads
# Installation
Clone the repository to your local machine:
git clone https://github.com/Ramzan-Ali12/daraz-scraper.git
# Usage
Open the terminal and navigate to the project directory:
cd daraz-scraper
# Run the script:
python scraper.py
The script will start scraping data from the Daraz website and display the progress on the terminal.
Once the scraping is complete, the collected data will be saved in a file named "product.csv" in the same directory.
# Important Notes
The script uses Selenium to automate the web scraping process. Make sure you have the necessary drivers and dependencies installed.

The script is designed specifically for any Product listings on the Daraz website. Modifying the script for other categories or websites might require adjustments to the class names and HTML structure.
Daraz's website structure might change over time, which can break the scraping script. Regular maintenance and updates may be needed to keep the script functional.



