# Scraper

Scraper/Annotator is an app that scrapes headlines and URLs
from the website EchoJS.  There is a link at the bottom  to
the /scrape route in case the user wishes to repeat the 
scraping process.  If the user clicks on one of the headlines,
text fields for a note title and text which the user can save.
The notes are specific to each headline, and are persistent.
The database is handled using MongoDB.

Here are npm packages used with this app:
express, morgan, mongoose, axios, cheerio, handlebars, path.

This app was adapted from my solution to a classroom exercise 
for the initial deploy, but I wasn't able to go beyond very 
basic functionality for this assignment.  Future enhancements 
would be to get handlebars templating working, adapting the 
scraper to work with another site, possibly have more advanced 
note-taking functionality, and major UI improvements.

The app is hosted on heroku at:
https://scraper1100.herokuapp.com/