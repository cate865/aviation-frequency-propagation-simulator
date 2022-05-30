# aviation-frequency-propagation-simulator
## Author: 
Catherine Muthoni

# Description
An aviation frequency propagation simulation implemented using Google Maps Javascript API, nodejs and MongoDB

# Frontend
In here is a map displayed via Google Maps Javascript API. It makes use of markers and overlays to display the display the different receivers which are fetched from the api

## How to run locally
- Open the folder "aviation-frequency-propagation-simulator_ui" in a text editor.
- Load the index.html file via a live server(ensure your backend server is live before doing this)

# Backend
In here is a simple API built using nodejs and using MongoDB as the database. It is responsible for creating, displaying and removing receivers.

## How to run locally
- Open the folder "aviation-frequency-propagation-simulator_ui" 
- Type "node index.js" on your terminal. The server should run on terminal 3000
- Use http://localhost:3000/receivers as the base url in your ui.js file(assets/js/ui.js) as well as index.js file on the frontend folder


