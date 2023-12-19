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
<img width="434" alt="Screenshot 2023-12-19 at 2 33 04 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/e98b9eac-faca-4fdb-9225-23f02adb38e5">

## How many Martian (and not Earth) days worth of data exist on the scraped dataset?
<img width="426" alt="Screenshot 2023-12-19 at 2 33 32 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/5b279ad3-428f-464d-9e5b-fa1e6e53ca49">

## What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
  * Find the average minimum daily temperature for all of the months.
    <img width="503" alt="Screenshot 2023-12-19 at 2 35 01 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/fe5feae2-db7a-47ed-9e20-25180fe526ed">
  * Plot the results as a bar chart.
    <img width="629" alt="Screenshot 2023-12-19 at 2 35 42 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/669c20b0-0020-49da-b1ee-de2bbbf6c5dc">
