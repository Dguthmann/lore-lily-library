# Lore-Lily-Library

### Author: David Guthmann

github: https://github.com/Dguthmann/lore-lily-library  
livesite: https://katsu-korokke.herokuapp.com/  


## List of Contents
To Be Updated Later

<!-- debug.log  
package.json  
package-lock.json  
README.md  
### public  
favicon.ico    
index.html    
logo192.png  
logo192.png  
manifest.json  
robots.txt  
### src  
App.js
index.js
#### components  
EmployeeList.js  
SearchEmployeeContainer.js  
SearchForm.js  
#### utils  
API.js   -->


## Installation
To Be Updated Later

<!-- you will need the following additional npms to run this project:  
axios  
bootstrap  
react  
react-dom  
react-scripts  
reactstrap  
web-vitals   -->


## Basic Overview of Project

The goal of the project is to model a google books search and add them to a mongo database.  


## Project Functionality

<!-- ![Site Screenshot](https://media.giphy.com/media/k3kF5UA98VFoTTs6km/giphy.gif)   -->


## Resources Used

<!-- Joe Rehfuss for search debugging especially with filter being non-destructive.  
Aslan Ghodsian for deployment auditing and help.   -->


## Further Development Plans

<!-- Styling and some hero cards would be nice to add when time permits, also having the tables have icons to show which direction it's sorted in.  Also to have better search functionality, which is also a limitation of the api used, in which all strings aren't lower cased.  This causes issues with the includes method used for the filter check.   -->


## Changelog

<!-- 2020-11-06: Working on sort, search functionality,   
2020-11-05: Creation of initial files, Routing and Axios Requests -->




## Create React Express App

## About This Boilerplate

This setup allows for a Node/Express/React app which can be easily deployed to Heroku.

The front-end React app will auto-reload as it's updated via webpack dev server, and the backend Express app will auto-reload independently with nodemon.

## Starting the app locally

Start by installing front and backend dependencies. While in this directory, run the following command:

```
npm install
```

This should install node modules within the server and the client folder.

After both installations complete, run the following command in your terminal:

```
npm start
```

Your app should now be running on <http://localhost:3000>. The Express server should intercept any AJAX requests from the client.

## Deployment (Heroku)

To deploy, simply add and commit your changes, and push to Heroku. As is, the NPM scripts should take care of the rest.
