# YCombinator News Web Scraper

This program scrapes the news from the YCombinator website (https://news.ycombinator.com/) and displays the titles, links, and votes of news items with more than 99 points. It uses the `requests` library to fetch the webpages and the `BeautifulSoup` library to parse the HTML content. The script combines the results from the first two pages of the news and sorts them by the number of votes.

## Requirements

- Python 3.x
- BeautifulSoup library
- requests library

## Installation

1. Clone the repository:

git clone https://github.com/bautiallende/WebScreap.git
cd ycombinator-news-web-scraper


2. Create a virtual environment and install the dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```
## Usage
Run the scrape.py script:

```bash
python scrape.py
```
After running the script, the titles, links, and votes of news items with more than 99 points from the first two pages of YCombinator news will be displayed in the console.

## Files
scrape.py: The main script that scrapes the news from the YCombinator website and displays the results.
