# module_11_challenge - Web Scraping

# Overview
In this challenge, I completed a full web-scrape and data analysis. I extracted information via automated browsing with Splinter and HTML parsing with Beautiful Soup.

# Technologies
* Splinter
* BeautifulSoup
* Matplotlib
* Pandas

# Part 1: Scrape Titles and Preview Text from Mars News
After inspection of the page to identify the proper elements to scrape, I created a Beautiful Soup object to extract the text elements (titles and preview text). Once extracted, the results were stored in a Python dictionary, which were then all stored into a list. 
<img width="559" alt="Screenshot 2023-12-19 at 2 23 16 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/e1c8703c-637a-40f1-a309-23069c69b9f2">

# Part 2: Scrape and Analyze Mars Weather Data
Once the list was created, I had scraped the data in the HTML table, and assembled the data into a Pandas DataFrame. The columns are as follows:
* id
* terrestrial-date
* sol
* ls
* month
* min_temp
* pressure

Because some of the data was not in the correct data type, I had utilized the as.type() function was used. 
<img width="685" alt="Screenshot 2023-12-19 at 2 31 29 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/fba9a10a-e77f-4e73-9d81-09ce5940a53b">

# Analysis
## How many months exist on Mars?

