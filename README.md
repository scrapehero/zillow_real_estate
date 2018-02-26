# Zillow Real Estate Listing Scraper

This script will scrape Zillow.com, an online real estate database to extract real estate listings available based on a zip code. If you would like to know more about this scraper you can check out our blog post at this link https://www.scrapehero.com/how-to-scrape-real-estate-listings-on-zillow-com-using-python-and-lxml/

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Fields 

This zillow scraper can extract the fields below

1. Title
2. Street Name
3. City
4. State
5. Zip Code
6. Price
7. Facts and Features
8. Real Estate Provider
9. URL

### Prerequisites

For this web scraping tutorial using Python 3, we will need some packages for downloading and parsing the HTML. 
Below are the package requirements:

 - lxml
 - requests

### Installation

PIP to install the following packages in Python (https://pip.pypa.io/en/stable/installing/).

Python Requests, to make requests and download the HTML content of the pages (http://docs.python-requests.org/en/master/user/install/).

To install python request module:

```
pip3 install requests
```

Python LXML, for parsing the HTML Tree Structure using Xpaths (Learn how to install that here – http://lxml.de/installation.html)
Installing lxml:

```
pip3 install lxml
```


## Running the scraper
You must run the script using Python with arguments for zip code and sort. The sort argument has the options ‘newest’ and ‘cheapest’
listings available. As an example, to find the listings of the newest properties up for sale in Boston, Massachusetts we would run the 
script as:

```
python3 zillow.py 02126 newest
```
## Sample Output

This will create a csv file:

[Sample Output](https://raw.githubusercontent.com/scrapehero/zillow_real_estate/master/properties-02126.csv)
 
 
