# Mars_News_Weather_Data
Web-scraping and data analysis project from websites containing Mars news and Mars temperature data.  This project utilizes automated browsing, web-scraping with Beautiful Soup, Python data structures, and Pandas DataFrames. 

Original code sources: Data Analytics course Module 11 Challenge Starter_Code files, Data Analytics course instructor, Andrew Hoang's, speed run Zoom recording for Module 11 Challenge

References
The Mars News website (https://static.bc-edx.com/data/web/mars_news/index.html) is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars News website (https://mars.nasa.gov/) in November 2022. Images are used according to the JPL Image Use Policy (https://www.jpl.nasa.gov/jpl-image-use-policy), courtesy NASA/JPL-Caltech.


See part_1_mars_news.ipynb jupyter notebook for web-scraping code. Webdriver from Selenium was used to visit the site, and HTML code was extracted using Beautiful Soup. Web-scraped data was stored in a list of Python dictionaries.


See part_2_mars_news.ipynb jupyter notebook for web-scraping code and data analysis/visualizations. Webdriver from Selenium was used to visit the site, and HTML code was extracted using Beautiful Soup. Web-scraped data was stored in a Pandas DataFrane. 

Data was analyzed to answer the following questions:
How many months exist on Mars?
How many Martian days' worth of data are there?

Data was analyzed to answer the following questions, and a supporting data vizualization was created using MatPlotLib:
Which month, on average, has the lowest temperature? The highest?
Which month, on average, has the lowest atmospheric pressure? 
How many terrestrial days exist in a Martian year? (Based on a visual estimate from the plot)

See output_data for exported DataFrame as a CSV file (mars_data.csv)