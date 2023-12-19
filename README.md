# Mars Web-Scraping

# Overview
In this challenge, I completed a full web-scrape and data analysis.

# Technologies
* Splinter
* BeautifulSoup
* Matplotlib
* Pandas

# Part 1: Scrape Titles and Preview Text from Mars News
After inspecting the page and identifying the appropriate elements, I used Beautiful Soup and Splinter to extract titles and preview text. The results were stored in a Python dictionary, then consolidated into a list.
<img width="559" alt="Screenshot 2023-12-19 at 2 23 16 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/e1c8703c-637a-40f1-a309-23069c69b9f2">

# Part 2: Scrape and Analyze Mars Weather Data
Once the list was created, I had scraped the data in the HTML table, and assembled the data into a Pandas DataFrame. Adjustments to data types were made using the 'as.type()' function. The columns are as follows:
* id
* terrestrial-date
* sol
* ls
* month
* min_temp
* pressure
<img width="685" alt="Screenshot 2023-12-19 at 2 31 29 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/fba9a10a-e77f-4e73-9d81-09ce5940a53b">

# Analysis
## How many months exist on Mars?
<img width="434" alt="Screenshot 2023-12-19 at 2 33 04 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/e98b9eac-faca-4fdb-9225-23f02adb38e5">

## How many Martian (and not Earth) days worth of data exist on the scraped dataset?
<img width="426" alt="Screenshot 2023-12-19 at 2 33 32 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/5b279ad3-428f-464d-9e5b-fa1e6e53ca49">

## What are the coldest and the warmest months on Mars (at the location of Curiosity)?:
  * Find the average minimum daily temperature for all of the months.
    <img width="503" alt="Screenshot 2023-12-19 at 2 35 01 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/fe5feae2-db7a-47ed-9e20-25180fe526ed">
  * Plot the results as a bar chart.
    <img width="629" alt="Screenshot 2023-12-19 at 2 35 42 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/669c20b0-0020-49da-b1ee-de2bbbf6c5dc">

## Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
 * Find the average daily atmospheric pressure of all the months.
   <img width="511" alt="Screenshot 2023-12-19 at 2 36 49 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/733efaf4-5e10-430e-a24d-187dbe58c455">

 * Plot the results as a bar chart.
   <img width="607" alt="Screenshot 2023-12-19 at 2 37 01 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/e8f7825a-3d99-48f2-8524-b4c841952dba">

## About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
 * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
   <img width="477" alt="Screenshot 2023-12-19 at 2 37 40 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/bda96ca1-8cd8-4204-b898-bbc72e53e056">

 * Visually estimate the result by plotting the daily minimum temperature.
   <img width="708" alt="Screenshot 2023-12-19 at 2 38 00 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/765a5f8d-6d74-430f-9255-6b7e464a8661">

Once these questions were answered, the DataFrame was exported to a CSV file for further use.
<img width="566" alt="Screenshot 2023-12-19 at 2 38 38 PM" src="https://github.com/samkimmmm/module_11_challenge/assets/135805393/dad1671d-5afa-450c-b43f-76bd4a916125">
