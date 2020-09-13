## What kind of cleaning steps did you perform?
___
* No cleaning steps were needed as I created a parsing method that scraped the webpages efficiently.
* Proper extraction the html attributes, allowed me to make an array to query into Alpha Vantage

## How did you deal with missing values, if any and were there outliers? How did you handle them?
___
* You cannot parse the end or total pages for FinViz in the search as BeautifulSoup has certain limitations.
* You would have to manually retrieve this in order to stop the loop.

___
### Overall, he API nor FINVIZ did not have any missing data due to the robustness of its data.
