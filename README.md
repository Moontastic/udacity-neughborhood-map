## Getting Started
To test this App in your machine, just follow the steps below:
- Clone this repo in your local ```git clone https://github.com/ChippX/neighborhood-map-react```
- Now into your folder project in the terminal exec ```npm install``` to install all dependencies
- After install all dependencies just execute ```npm start``` on the terminal.
- The browser will automatically open the Neighborhood Map App. If it doesn't, please [click here](http://localhost:3000/)
### Offline First
- The service worker is only enabled in the production environment. It's recommended that you do not enable an offline-first service worker in a development environment.
- If you need to **test your offline-first** service worker locally, build the application (using `npm run build`) and run a simple http server from your build directory.
- More information [Here](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#offline-first-considerations)


## Technologies & Packages:
* [Reactjs:](https://reactjs.org) A JavaScript library for building user interfaces.
* [MediaWiki:](https://www.mediawiki.org/wiki/API:Main_page) It is a web service that provides convenient access to wiki features, data, and meta-data over HTTP, via a URL usually at api.php.
* [Google Maps JavaScript API:](https://developers.google.com/maps/documentation/javascript/tutorial) It lets you customize maps with your own content and imagery for display on web pages and mobile devices.
