# Scrape

This app is a simple web scraper for ESPN headlines. Here's how to use it:
- Install the node packages with npm install
- Start up mongo and create a database called "takehome"
- Start the server from the terminal with the command "node server.js"
- visit localhost:3000 to get a "Hello World" message
- visit localhost:3000/scrape to start the scraping, if all went well you'll get a "Scraping completed." message
- visit localhost:3000/all to see the titles and links of each headline scraped and pushed into the database