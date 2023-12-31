# 2023 Uber Global Hackathon Hyperson\<i\>c team Submission\: UberWalk

UberWalk is a web application developed by Hyperson\<i\>c as the submission for the coding track of the 2023 Uber Global Hackathon. The application takes three user-input addresses\: the user's address, the destination address, and the driver's address. With this, the application calculates an optimal pickup point where the user and the driver arrives at the same time. UberWalk reduces travelling time, limits emissions from ridesharing services, and improve affordability for low-income individuals.

## Using the Application
To use the application, click this [link](https://uber-walk.vercel.app/). <br>

You will be shown a landing page with instructions and an HTML form at the button. After entering in the addresses and clicking the submit button, you will be shown the pickup location, how long it takes to walk there, the savings, and a map. <br> 

Here are example addresses, taken from a simple Google Maps search\: <br>
<strong>your location\:</strong> 110 Wellesley St W, Toronto, ON M7A 1A2 <br>
<strong>your destination\:</strong> 290 Bremner Blvd, Toronto, ON M5V 3L9 <br>
<strong>the driver's location\:</strong> 235 Bloor St E, Toronto, ON M4W 1C8 <br>

## Troubleshooting
When "Internal Server Error" is displayed, it means there's some kind of problem with how our backend is handling things. Here are some common problems and ways to fix them.
* The backend does not accept the address\: make sure the address is in proper format and exists. To be certain, use addresses provided by Google Maps.
* You did not input the proper number of inputs\: make sure you have entered the correct number of addresses.

## Contribution Guidelines
No one is allowed to contribute to our project, as the submission must be strictly the original and unique work of Hyperson\<i\>c. You (including judges) are allowed to view the files of this project and use the applicaiton via the link.

## Credits
### Built With
* Python Client for Google Maps Services - External Library
* Flask - Web Framework
* Vercel - Web Hosting

Hyperson\<i\>c used functions from the Python Client for Google Maps Services. These functions are\:
* gmaps.geocode
* gmaps.reverse_geocode
* gmaps.distance_matrix

Hyperson\<i\c used functions from Flask. The logic and the way we used these functions are our original work.

All other code is made my Hyperson\<i\c.

### Hyperson\<i\>c 
Hyperson\<i\>c consists of four members\:
- Kirk Poppa\: Team Leader
- Thomas Duong\: Co-Leader
- Andrew Li\: Member
- Luiz Guilherme\: Member

![Team logo.](https://i.ibb.co/51bgVL5/UGHlogo.png)
