# Swiggy-Restaurants-Data-Scraping

Context

Swiggy is an Indian online food ordering and delivery platform. 
Founded in July 2014, It is based in Bangalore and operates in 640 Indian cities as of September 2022 (which was 500 as at September 2021). Swiggy is the most on-demand food delivery platform that brings food from neighborhood restaurants directly to customers' doors.

About
This is web scraping project where i Scrape Swiggy's Top Rated Restaurants for all listed cities in India using Python packages like Requests, BeautifulSoup, numpy, and Pandas. The source of data set is Swiggy's official website. Here is the link - https://www.swiggy.com

Project outline
We grab all the hyperlinks on the swiggy landing page, and filter out Swiggy Restaurant listing for all 640 locations across India.

The goal is obtain information like name, cuisine, location, rating, number of ratings, and price for two for each restaurant and save them in 'rest_swiggy.csv'.

