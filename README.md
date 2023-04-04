# Mars_Webscraping

## Overview
Utilizing webscraping tools, scrapped and analyzed information from two websites.  This project consisted of two parts.
Part 1 pulled and imported titles and previews of news articles from [Red Planet Science](https://redplanetscience.com/), cleaning the data and importing into a list.  
Part 2 consisted of pulling data from a [AWS Warehouse](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) scrapping and analyzing the data.

## Summary Part 2
Plot 1 - Concluded on average the coldest tempature on Mars is in its third Month and the warmest month is the eight month.
![image](https://user-images.githubusercontent.com/109490755/229853492-276d8b44-1c8e-4af6-a0a0-6e2400c0a7e3.png)

Plot 2 - Verified the atmospheric pressure on Mars on average is lowest in the sixth month and highest in the ninth.
![image](https://user-images.githubusercontent.com/109490755/229853359-044292eb-84d9-4eab-9d6a-288555600e0a.png)

Plot 3 - The distance from peak to peak on Plot 3 is roughly 1425-750 Z(as shown on the graph), or 675 days. After reviewing on the internet 687 earth days are equal to 1 Mars year.
![image](https://user-images.githubusercontent.com/109490755/229853296-1dd36496-ce7d-41ef-a666-abb92131a38b.png)



### Proposed Changes

After compiling the data from the [AWS Warehouse](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) using beautiful soup it would be a more effective and quicker to read the dataframe using Pandas,  we could skip steps 2-3 as the data would already be cleaned and in a dataframe.

### Tools

Beautiful Soup - To scrape data from websites

Splinter - to establish and executable path within Jupyter

Jupyter Notebook

Matplotlib

Pandas
