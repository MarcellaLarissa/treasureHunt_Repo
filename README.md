Treasure Hunt Web App
A Group Project with Adam Silver

The Treasure Hunt Web Application is an interactive tool that allows users to
create or play a ‘treasure hunt’ based on historical, cultural, and local attractions.
This platform is designed to engage locals and visitors alike in appreciating the
treasures their neighborhood has to offer.
This app uses Google products for its server, database, and user authentication.
It uses Google Maps API and geolocation services to create maps and interact
with the user’s location during gameplay. A REST API is used to facilitate the
interaction between the front and back end.

Back End 
(Adam Silver wrote/implemented these programs and tools)
The server and database are on Google Cloud Platform using
Python, Flask, and REST API. Login and User Management were set up using Auth0, a third party OAuth
authentication site, and JSON web tokens.

Front End
(Marcella Petrucci wrote and implemented these, in with collaboration Adam Silver)
The webapp uses Google Maps API for creating maps and getting user location information and a basic stack of 
html, css and javascript with jquery library calls to the server.


Note:
The team's intention was to use location tracking and
geofencing techniques through the Google Maps API to track the user’s location
in relation to the clues and treasure locations while playing a hunt. Further
research showed that location tracking of a user, as understood by the team, is
not available through the browser. The team devised an alternative approach to
use a button clicked by the user to update the user’s distance from the target
location. Once the location returned by the click event is close to the clue, the next clue in the sequence will
pop up on the map. This will be repeated until the treasure is found.
