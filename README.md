# Yummy App

## What?

Yummy app is a food app that has two main categories which are: 
* Food
* Drinks

On clicking on a category, a list of food or drinks available on our app will be displayed to the user.

## How? 
* We discussed the project idea and its purpose with the team.
* We agreed on a schema for our database.
* We worked first on building sql and connecting server with database to select and insert data. 
* We built server and handle differnt requests.
* We rendered results to users on the dom.
* We handled errors and displayed clear messages to the user.

# Schema:

![](https://files.gitter.im/alaabadra/ZqxS/yummy.png)

## User Story

* The user want to search for a job name and description.
* The user wants to know if there are any problems or error such as noresults found, not found page, server internal error and empty input.

## Architecture

1. public
	css
	  styles.css
	js  
	  dom.js
	  fetch.js
	index.html
	html 
	  notFoundPage.html
	  serverInternalError.html
2. src
	* Database
	  * db_build.js
	  * db_build.sql
	  * db_connection.js
	* Queries
	  * getData.js
	  * insertData.js

*  handlers.js
*  makeRequest.js
*  router.js
*  server.js
3. test
   * testQuery.js
   * servertest.js
4. README 
5. .gitignore 
6. package-lock.json 
6. package.json 

## Skills We Used:

1. Making schema and building connection to database.
2. Hosting our databse remotly on Heruko.

3. Basic back-end services, such as building HTTP server. 
4. Modularizing our app. 
5. Testing our Functions.
6. Hosting our project on heroku.
7. Using module.exports and require to break a single large server file into smaller modules.
8. Make request to api in the back-end.
9. Handle Errors.

