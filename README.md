# Mars_Webscraping

## Overview
Utilizing webscraping tools, scrapped and analyzed information from two webistes.  This project consisted of two parts Part 1 pulled and imported titles and previews of news articles from https://redplanetscience.com/, cleaning the data and importing into a list.  
Part 2 consisted of pulling data from https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html scrapping and analyzing the data.

## Summary Part 2
Plot 1 - Concluded on average the coldest tempature on Mars is in its third Month and the warmest month is the eight month.

Plot 2 - Verified the atmospheric pressure on Mars on average is lowest in the sixth month and highest in the ninth.

Plot 3 - The distance from peak to peak on Plot 3 is roughly 1425-750 Z(as shown on the graph), or 675 days. After reviewing on the internet 687 earth days are equal to 1 Mars year.

### Proposed Changes

After compiling the data from https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html using beautiful soup it would be a more effective and quicker to read the dataframe using Pandas,  we could skip steps 2-3 as the data would already be cleaned and in a dataframe.

### Tools
Beautiful Soup - To scrape data from websites
Splinter - to establish and executable path within Jupyter
Jupyter Notebook
Matplotlib
Pandas
