# FriendFinder

The FriendFinder app is written in JavaScript and uses ExpressJS. After being prompted to fill out the survey, the information is parsed and matched with other users input and a friend is suggested based on an algorithm.

# Technologies used:

* BootStrap
* JS
* ExpressJS
* HTML
* NodeJS
* CSS


 # Overview of functionality

* Modularity in the form of separate files for server logic, storing of friends, views, and routing
* 10-question survey to assess uniqueness of users
* Use express, body-parser, and path npm packages in the server.js file
* Separate JavaScript files for routing (htmlRoutes.js and apiRoutes.js)
* Appropriate GET and POST routes for serving HTML pages and API calls
* Separate file for storing friends (friends.js)
* Calculate best match for user once survey is completed and return that match to the user