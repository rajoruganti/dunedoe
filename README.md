- App detects user location
- User sees places of interest at zoom level 100km 
- User sees path to destination; type of path indicates type of transport [straight line for flight, wiggly train path, wiggly highway + combinations]
- User sees theme attributes indicated by:
-- color of path [cost of travel]
-- thickness of path [ease of travel]
-- type of line - dash gap [speed of travel]
-- type of icon [destination type]
- user can change themes [cheap/lux, easy/hard, slow/quick]
- user can zoom in and out to see details adjusted appropriately (more fine grained when zooming in)

# TODO
- [ ] create-react-app
- [ ] Install react-leaflet: https://github.com/PaulLeCam/react-leaflet
- [ ] Get a map on the page!
- [ ] Get the users location
- [ ] with the browser
- [ ] with their IP using an API
- [ ] Show a pin at the users location
- [ ] Setup server with create-express-api: https://www.npmjs.com/package/create-express-api
- [ ] Add monk and joi
- [ ] POST /messages
- latitude
-  longitude
-  name
-  message
-  datetime
- [ ] When the page loads get all messages
- [ ] GET /destinations
- [ ] Add pins to the map
- [ ] Click a pin to see the message
- [ ] 
- [ ] Show a form to submit selection
- cost
- ease
- speed
- [ ] when form is submitted - POST /destinations
- send params 
- run query
- [ ] refresh map
- [ ] when user zooms - POST / destinations
- send coords
- run query
- [ ] DEPLOY!
 https://dunedoe.app
- [ ] Refactor React app
- [ ] seperate components
- [ ] seperate file for API requests
- [ ] seperate file for Location requests
