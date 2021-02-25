# Budget-Tracker
Online/Offline Budget Tracker

## The Project
Add functionality to our existing Budget Tracker application to allow for offline access and functionality.
The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling.

## Business Context
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

## Table of contents
* The models folder containing the transaction.js file https://github.com/BeresIvan/Budget-Tracker/tree/main/models
* The node modules folder with the modules
* The public folder includes the Assets folder, Icons Folder, db.js, index.html, index.js, manifest.webmanifest , service-worker.js and the style.css files. https://github.com/BeresIvan/Budget-Tracker/tree/main/public
* The routes folder containes the api.js folder https://github.com/BeresIvan/Budget-Tracker/tree/main/routes
* Our main application folder also containes .env, .gitignore, paackage-lock.json, package.json, REAEDME.md and the server.js files. https://github.com/BeresIvan/Budget-Tracker

