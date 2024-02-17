# web-scraping-challenge

Bootcamp Module 11 Web-Scraping homework exercises

## Background to Challenge

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their `id` and `class` attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

## Deliverables

- Deliverable 1: Scrape titles and preview text from Mars news articles.

- Deliverable 2: Scrape and analyse Mars weather data, which exists in a table.


## Data Locations
- Part 1 Jupyter notebook: `part_1_mars_news.ipynb`
- Part 2 Jupyter notebook: `part_2_mars_weather.ipynb`
  - Output from Part 2: `output/mars_dataset.csv`

[!Important Note]
In Part 2 where we need to estimate how long it take for Mars to orbit the sun, I have created another column in the Mars data table to calculate the days since the beginning of the dataset. This is important because this dataset **doesn't** have data recorded on every day. For example, there is **no** data between dates  2012-08-23 and 2012-08-27. Therefore simply having a count of items along the x-axis of the line-plot is misleading and is not representative of  the dataset.