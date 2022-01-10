# AZLyrics_Scraper
This is a scraper for the lyrics website AZLyrics. With this scraper you can collect metadata about the songs, albums and publication year as well as the lyrics of the songs themselves. This is all neatly wrapped together in a Juypiter Notebook. The output of the Notebook will be a csv file with the previously mentioned data.

## Notebook use

Running the Juypiter Notebook will only require a link to the artist's page you want to scrape. You can paste that link by replacing the link at the very top of the Notebook. 

In the scraping code for in the Notebook you can find two timers which artificially slow down the code so you don't get blocked by AZLyrics. You can select either of the two based upon how many songs an artist has in their catalog. By default the Notebook is set to the short timer which allows for around <100 songs to be scraped.

## Known issues:

As of yet the scraper is not able to collect songs from the 'other songs' catagory due to an issue with an error regarding the get_element_text function disrupting the scraping.
