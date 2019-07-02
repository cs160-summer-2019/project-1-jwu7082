# P1
* In-depth assignment description in the Google Doc [here](https://docs.google.com/document/d/18VBl8AfogpKVgx7QG7TTYnWRRpO8nH_w53q8Rxrk1H4). 
* Front-end created using Sass (SCSS), minimal Bootstrap (Grid, carousel, red alert card), and the Mapbox API. 

### Index
* File: `weather/templates/weather/index.html`
* URL: http://project-1-starter-code-jwu7082-jwu7082387298.codeanyapp.com:8000/weather/

### Files Edited
* Forecast (single location) no alert: `weather/templates/weather/index.html`
* Forecast (single location) with alert: `weather/templates/weather/warning.html`
* Comparison across locations no alert: `weather/templates/weather/index.html`
* Comparison across locations with alert: `weather/templates/weather/warning.html`
* CSS for styling: `weather/static/weather/css/style.css`

### URLs to access
* Index: http://project-1-starter-code-jwu7082-jwu7082387298.codeanyapp.com:8000/weather/
  * Includes forecast (single location) and comparison across multiple locations

* Forecast (single location) no alert: `weather/templates/weather/`
* Forecast (single location) with alert: `weather/templates/weather/warning/`
* Comparison across locations no alert: `weather/templates/weather/`
* Comparison across locations with alert: `weather/templates/weather/warning/`

### App Preview/Information
* The app was intended to change gradient colors based on the time of day. The previews below are for sunset.

#### Missing features from wireframe: 
* Temperature labels on map location markers 
* Time selector to change the hour of the displayed temperatures on both the map and saved city cards (enables users to view forecasts of nearby/saved locations at a specific time)
* Sticky button on bottom right corner of city cards to edit list of saved cities 
* Delete card feature upon clicking a city card
* Mile drop-down menu on map to adjust radial distance of nearby cities
* Button toggles to switch between Fahrenheit/Celsius or Hourly/Daily forecasts

#### App Preview: No Extreme Weather Alert
![](app_no-alert.gif)

#### App Preview: With Extreme Weather Alert
![](app_alert.gif)
