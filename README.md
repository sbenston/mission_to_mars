# mission_to_mars

## Overview of Project

Analyzes data about the Red Planet, Mars, starting with gathering the data via web scraping. Two websites where scraped, one for news articles to gather the title and preview summary information to store as a Python dictionary and then a JSON file for easier access. The second website pulled a table of recordings from the Curiosity rover to make a Pandas Dataframe which was then cleaned. As a DataFrame details such as the average minimum temperature over the course of the Martian months were analyzed as well as plotted with Matplotlib.

The websites https://redplanetscience.com/ and https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html where the sources of data used in the project. Web scraping was accomplished using the BeautifulSoup package with automated browsing via Splinter.
