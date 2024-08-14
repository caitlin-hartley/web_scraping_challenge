# web_scraping_challenge

![mars](https://github.com/caitlin-hartley/web_scraping_challenge/blob/main/output/mars_weather.webp)

[Part 1: Scrape titles and preview text from Mars news articles](https://github.com/caitlin-hartley/web_scraping_challenge/blob/main/README.md#part-1-scrape-titles-and-preview-text-from-mars-news)

[Part 2: Scrape and analyze Mars weather data](https://github.com/caitlin-hartley/web_scraping_challenge/blob/main/README.md#part-2-scrape-and-analyze-mars-weather-data)

---


## Part 1: Scrape Titles and Preview Text from Mars News

- Use automated browsing to visit the Mars news siteLinks to an external site
- Create a Beautiful Soup object and used it to extract text elements from the website
- Extract the titles and preview text of the news articles
- Store the scraping results in Python dictionary with two keys: title and preview
- Store all the dictionaries in a Python list

![dictionary](https://github.com/caitlin-hartley/web_scraping_challenge/blob/main/output/mars_dictionary.png)

---

## Part 2: Scrape and Analyze Mars Weather Data

- Assemble the scraped Mars weather data into a Pandas DataFrame
- Analyze your dataset by using Pandas functions to answer the following questions:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  
### What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
 - The coldest month is 3, and the warmest month is 8

![temp](https://github.com/caitlin-hartley/web_scraping_challenge/blob/main/output/avg_low_temp_sorted.png)

### Which months have the lowest and the highest atmospheric pressure on Mars?
- The month with the lowest atmospheric pressure is month 6, and month 9 has the highest atmospheric pressure

![pressure](https://github.com/caitlin-hartley/web_scraping_challenge/blob/main/output/avg_pressure.png)

### About how many terrestrial (Earth) days exist in a Martian year?
- Based on the graph, there are approximately 675 Earth days in a Martian Year
  
![earth days](https://github.com/caitlin-hartley/web_scraping_challenge/blob/main/output/daily_min_temp.png)
