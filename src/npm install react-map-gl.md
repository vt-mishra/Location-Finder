npm install react-map-gl
npm install axios
npm install react-icons

Go to the website: https://www.mapbox.com/ and create a free account.
Go to your account dashboard and at the bottom of the page you will find a section named “Access tokens”.

Copy the default public access token and save it somewhere to use it later.
Now in the App.js component, we will import the map using the react-map-gl package. Inside the map, we will use a marker to pinpoint the exact location by the coordinates and also a search box where users can type any city/location name. For more information related to react-map-gl visit their official https://visgl.github.io/react-map-gl/. Now write down the following code in the App.js component.

Remember to replace <YOUR_API_KEY> with your own Mapbox public access token.

In the App.js component, we have also imported our own custom component named “Fly” which is nothing but a simple box that takes user input, calls a forward geocoding API (https://docs.mapbox.com/api/search/geocoding/) provided by Mapbox itself, and sets the coordinates accordingly. Let us create that component.

Create a folder under the src folder named “Components” and under that folder create a file named “Fly.jsx“

Filename: Fly.jsx Now write down the following code in the Fly.jsx file.

Remember to replace <YOUR_API_KEY> with your own Mapbox public access token.

Filename: App.css Now let’s edit the file named App.css to style our app.