
Amazon-Scraper: Find Your Perfect Item!
Overview
Amazon-Scraper is a Python-based tool that allows you to scrape multiple Amazon web pages for specific items. It supports setting price ranges, outputting results to CSV/JSON, and more.

Features
Scrape multiple Amazon web pages for a specified item
Set price ranges (lower and upper bounds)
Output results to CSV or JSON
Option to find and print the cheapest item

Technologies Required
Python: Download Python
Pip: Install Pip
Git: Install Git

Python Dependencies
BeautifulSoup4 (bs4)
requests
lxml
rich

Installation
Clone the Repository:
mkdir "Amazon Scraper"
cd "Amazon Scraper"
git clone https://github.com/Moffi-bit/Amazon-Scraper.git
Install Dependencies:
py -m pip install bs4 requests lxml rich

Usage
Navigate to the project directory
cd Amazon-Scraper

Command Line Arguments
-i, --item: Specify the item to search for (required).
-l, --lower: Set the minimum price.
-u, --upper: Set the maximum price.
-n, --num: Specify the number of item links to scrape (required).
-c: Output the cheapest item.
-o, --out: Specify the output file name for CSV/JSON.
