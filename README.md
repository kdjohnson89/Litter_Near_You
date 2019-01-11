# Litter_Near_You
"Poo near you" project from Raspberry Pi

## Intro

This project was created using HTML/CSS/JavaScript.

Litter Near You utilizes Google Maps and data from [Nottingham Open Data page](https://www.opendatanottingham.org.uk/dataset.aspx?id=124) to show incidents where either litter was dropped, or someone did not pick up after their dog.
 
## Instructions for download

Download zip file for project. 

Obtain a Google Maps API key:

- An API (or Application Programming Interface) is a set of functions that allow you to interact with another computer—in this  case the Google Maps server. You need to have an API key to access it, so that Google knows who it has allowed to use its    services.

- You will need to create a Google account, or use an existing Google account, to obtain an API key. There is a minimum age requirement for creating an account which varies form country to country—please check this page first to see whether you are old enough.

- Open this page and, under the heading “Step 3: Get an API key”, follow steps 1-4 to obtain a Google Maps JavaScript API key.

- To use your API key in a HTML page, open the HTML file and locate the following:

`<script async defer
  src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
</script>`

- Find the part in the code you just pasted which says YOUR_API_KEY, and replace it with the API key you’ve generated. Make sure there are no spaces between the key you paste in and the = and & characters on each side of it.

In your terminal, setup a local web server in the project folder directory:
 -Windows: `python -m http.server`
 -Raspberry Pi and Mac: `python3 -m http.server`
 
Open your web browser and type http://localhost:8000/index.html. Press enter.
