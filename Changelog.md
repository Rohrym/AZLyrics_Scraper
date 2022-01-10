# Changelog
## AZLyrics Scraper V1
### Features:
- Scraping song data from artist pages. The data includes: song name, album, album release, credits and lyrics.
- This data can be exported to a csv file called 'songs.csv'
- The data can be opened in the Notebook in a Pandas dataframe.
## AZLyrics Scraper V2
### New features:
- Added a timer feature to the scraping code.
### UI:
- Changed one instance where .text.strip() was used instead of the function get_element_text().
## AZLyrics Scraper V3
### New features:
- Added an additional timer for artists with large catalogues.
- Added a way to scrape 'genre' from AZLyrics webpages.
- Added an 'id' column to the csv.
- Pandas dataframe now fills 'NaN' spaces instead of dropping lines with 'NaN'.
- The output csv file will now be automatically named after the band whose data has been scraped.
### Bugfixes:
- Fixed an issue where EP's and Compilation albums were not displayed correctly.
- Fixed an issue where the wrong text got scraped instead of the credits.
### UI:
- You can now change the link from the start of the Notebook.
- Removed 're' library as it was no longer in use.
- Removed some code used previously for testing purposes.
