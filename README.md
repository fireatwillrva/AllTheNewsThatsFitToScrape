# New York Times Article Scraper
Mongo Scraper is an app that scrapes articles from the New York Times website and lets users write and save notes for each article.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- npm packages
    - body-parser
    - express
    - mongoose
    - cheerio
    - axios

## How It Works
- Scrape articles by clicking the "Scrape Articles" button.
- Once articles are loaded, read full articles by clicking the link in each article's section.
- Add a note to an article by clicking on its section, creating a note to the right. Type your message and click "Save Note".

## Demo

Check out the application [here](https://newyorktimes-mongo-scraper.herokuapp.com/) on Heroku.
View a demo of Mongo Scraper and how it interacts with a Mongo database [here](https://youtu.be/hYCdYJ2912w) on YouTube.

### Installation

To install the application, open the terminal or command prompt and follow the instructions below:

``` Javascript
	git clone git@github.com:fireatwillrva/MongoScraper.git
	cd MongoScraper
	npm install
```
	
### Running Locally

To run the application locally and access it in your browser, open [server.js](./server.js) in the terminal and run the command below.

``` Javascript
	node server.js
```
	
The application will now be running locally in your browser at the URL `http://localhost:3000`. *Happy scraping!*
