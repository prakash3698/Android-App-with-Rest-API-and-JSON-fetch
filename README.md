# Android-App-with-Rest-API-and-JSON-Call

This is a mobile app completely developed using xml and java. This app interact with the server Using RESTapi, And fetches the JSON files from the server and displays it in a customised ListView.

# Languages Used

XML for frontend
JAVA for business logic
PHP for server scripts
MySql Queries for Database communication 

# Design

The User Interface of the app is designed in Adobe XD

# API's Used

Volley Client is used to fetch and display json data from the URL provided as a response from the server.
REST API written in PHP for Signup and Login process.

# Working

The app uses sharedprepherences to manage the login sessions and one time activity, The Signup page appears only when the app run for the very first time after Installation. Once after the signup, it directly Takes to the homeScreen of the app. Only if the user log's out from the app it takes to the login page, else it directly takes to the home screen even after quiting the app from background.
From the home Screen it Takes the choice of the user to switch between catogories displayed, and fetches the Json file from the unique URL generated for every single User.
