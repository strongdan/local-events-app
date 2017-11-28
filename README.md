# Local Events App
JS Web App that Scrapes Websites for Local Event Information

* Scrapes websites and matches location information for events in a specific location
* Uses [Simplecrawler](https://github.com/simplecrawler/simplecrawler) for web scraping
* Uses [CosmicJS Static Site Generator](https://github.com/cosmicjs/static-website)
* Uses a database to store event information: title, datetime, location, category, organization, description
* Displays three columns: (1) Today's Events, (2) Categories, and (3) Month Calendar
* Allows users to update calendar with new events
* Uses FB Graph API to get events by city https://stackoverflow.com/questions/13409763/is-there-any-way-to-fetch-all-facebook-events-in-a-specific-city
* Uses static email sender running on Lambda created by @craftzdog https://github.com/craftzdog/send-email-lambda
* Uses Bootstrap calendar created by @Serhioromano https://github.com/Serhioromano/bootstrap-calendar


* Visit site [here](http://danstrong.tech/local-events-app/)
