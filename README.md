# Venue Registration System
Welcome to the Venue Registration System. The Venue Registration System(VRS) is a place where you can get the perfect venues for your events.

# Here's a brief introduction to how to use our service in your systems:

Software you need:
1) MongoDB Compass
2) Node.js
3) Install express, mongoclient and cors for this node.js
4) A browser, preferably Google Chrome
   
Steps to save VRS in your system:

1) Make a folder for this system.
2) Save the assets, frontend to this folder.
3) Also, save the server.js to this folder, it's better to save it in a folder named backend.
4) Create a connection named "venues" in mongoDB Compass, in it create 3 databases name "vTenali1", "vGuntur1" and "vVijaya1". Create collection in these database with the same name.
5) Import the json files in the mongodbcollections folder in these collections as per their names.

Steps to run VRS in your system:
1) Run this server.js file using node.js with the command "node server.js". You can run this file by executing the command in the command prompt, make sure that the cmd is the folder for VRS.
2) Make sure the mongoDB Compass is running in the background, you can achieve this by executing the command "net start mongodb"
4) Start navigating the VRS with homepage.html in the frontend folder and enjoy our system
5) It's best to check that the "venues" connection string in your mongoDB Compass and the one in the server.js file matches, by defualt it will be "localhost::\27071/"

How to use VRS:
1) Click the "Get Venues Now!" option in the navbar
2) Fill the form and get suitable venues.
3) Login to save your venues
4) You can check the logged data in localStorage of your browser.
5) You can also check the user login credentials the mongoDB database "users" in the "venues" connection.

