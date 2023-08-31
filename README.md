# HTML SCRIPTING & DATA ANALYZATION
![image](https://github.com/sorapmas/html-scripting/assets/128443029/3c1f6a35-d3a7-4b27-b92e-caeef6dec337)

## Background:
The goal for this respistory is to extract information using both automated browsing with Splinter and HTML parsing with Beautiful Soup to deliever, 
- ***Part 1 Deliverable:*** Scraping titles and preview text from Mars news articles.
- ***Part 2 Deliverable:*** Scraping and analyze Mars weather data, which exists in a table.

This repository contains the following:

    ANALYSIS
  - ***part_1_mars_news.ipynb:*** A jupyter notebook used to scrape data from an html NASA Mars website, for the text of tiles and previews of the news articles.
  - ***par_2_mars_weather.ipynb:*** Also a jupyter notebook that scrapes numerical data off of an html website used to analyze the weather for Mars.
  - ***chromedriver:*** Provides the resource to navigate to the webpage needed in order for our code to work

        DATA
  - ***mars_weather.csv*** A heavy CSV file that reads the numerical data on Mars weather which stores information for each of the columns such as id, terrestrial_date, sol, ls, month, min_temp, and pressure. 

        ANALYING MARS WEATHER DATASET
    - ***How many months exist on Mars?*** There are 12 months on Mars.
    - ***How many Martian days worth of data exist in the scraped dataset?*** There are 1867 Martian days.
    - ***What are the coldest and the warmest months on Mars (at the location of Curiosity)?*** The third month is the coldest month sitting at just over -80°C, and the hottest motnh is the eight month which is a little under -70°C.
    - ***Which months have the lowest and the highest atmospheric pressure on Mars?*** The sixth month was the lowest atmospheric pressure on Mars which reads 745.0, while the highest reads 913.3 for the ninth month.
    - ***About how many terrestrial (Earth) days exist in a Martian year?*** Based off the last graph shown, you are able to see the three highest peaks which represent the sun circling around the planet each year. Now if we divide that by the number of days which is 2000. There would be 666 Earth days that exist in a Martian year
    
    
