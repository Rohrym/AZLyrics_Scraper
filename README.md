# AZLyrics_Scraper

This is a scraper for the lyrics website AZLyrics. With this scraper you can collect metadata about the songs, albums and publication year as well as the lyrics of the songs themselves.
This is all neatly wrapped together in a Juypiter Notebook.

Running the Juypiter Notebook will only require a link to the artist's page you want to scrape. You can paste that link by replacing the link at the very top of the notebook. 
The output of the Notebook will be a csv with the data. The csv will be named after the last part of the url you pasted in the Notebook.

Known issues:
- As of yet the scraper is not able to collect songs from the 'other songs' catagory due to an issue with an error regarding the get_element_text function disrupting the scraping. 
