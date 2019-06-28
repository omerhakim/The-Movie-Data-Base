# The-Movie-Data-Base
## Using API and Web Scraping with the Movie Data Base

Project Contributors: Mohamad Eldebek and Omer Hakim

## Goals:
The goals of our project were to find data about movies that can give investors new ideas regarding possible investments.

## Method of Work:
The first phase was cultivating data from “The Movie Data Base”. We used API key to get the data, and we sorted out information regarding votes count and votes averages.We were looking for correlation between the two. We did the sorting with running a loop who sorts the information into a SQL database. Later we uses pandas to group and visualize the data.
The second phase was scraping data from Wikipedia about the nominees for the academy award for foreign language film (from 1956 onward). We used BuetifulSoup for the scraping the information and store it as a pandas data frame. Later we imported csv file from the the UN website (with information regardind the world population) and merged it with our scraped pandas Data frame. Based on this data we were looking for interesting opportunities of investment in the film industry abroad.
