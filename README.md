# Real Time Bus Tracker
Tracks active locations of bus transit in the city of Boston. Location information provided from MTA (Massachusetts Transportaton Authority).

Base file supplied to me gave me the function to pull data from MTA every 15 seconds.

Added mapping information using the API provided by mapbox and my own access key which I have removed for security.
  In order to get the website to display you will need to paste your own access key in the script tag in the quotes to the right of the mapboxgl.accesstoken.

## What Have I done?
Added logic to use data supplied from MTA to generate a bus icon that:
  * corresponds to the current location
  * color changes based on occupancy status, green for many seats available, yellow for default, and red for few seats available
  * when moused over displays bus id number and current stop
I was provided GPS location data of bus stops between Harvard and MIT in an earlier project which I provided in this one as well.

## Planned Improvements
* Expand busstops showing to match current active bus routes.
* Add legend on map to display color coordinated route info to active buses for easier tracking of future and past stops
* Keep track of average run times to give user an estimate of time before a bus reaches the chosen stop.
