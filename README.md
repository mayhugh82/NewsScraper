# NewsScraper

This is a web app that lets users view, save and add notes to the latest articles displayed at [NPR's website](https://www.npr.org/).

Whenever a user visits the site, the app scrapes stories and displays them for the user. The user can then save articles for later viewing. Once an article is saved, the user can add notes to the article and delete each note. Each scraped article, and its corresponding notes, is saved to a Mongo database. The app scrapes and displays the following information for each article:

* Headline - the title of the article

 * Summary - a short summary of the article

* URL - the url to the original article

## Links to Deployed Versions

[Github](https://github.com/mayhugh82/NewsScraper)

[Heroku](https://newsscraper-npr.herokuapp.com/)

## Technologies Used
* Node.js - open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser
* Express.js - build server-side routes and functions
* Mongoose (Mongo DB) - define schema, create custom methods to fetch data, create relationships between collections (tables)
* Cheerio- scrapes articles from https://www.npr.org/
* Axios - a promised-based http library, similar to jQuery's Ajax library. It works on the client and on the server.

## To run the application

Just run "npm install" in a terminal window after cloning the project. The required packages will be fetched from the package.json file and installed on your machine.

## Author
* **Diana Mayhugh**