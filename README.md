# another chrome weather extension

## about

**acwe** is a chrome extension that will override the default chrome "new tab" page into a minimalistic page features the essentials—a google search bar and handy weather information.

## weather data

the weather data is requested from the [national weather service's](https://www.weather.gov) public api which uses a system of gridpoints to issue forecasts. 

accordingly, the extension makes an initial request using the browser's location to determine the user's gridpoint, and sends subsequent requests using the gridpoint to fetch weather data.

read more about gridpoints and the NWS api [here](https://weather-gov.github.io/api/gridpoints).

## requirements 

- an internet connection
- google chrome

## installation

 1. clone or download the github repository
 2. move contents into a new folder
 3. go to `chrome://extensions/`
 4. enable developer mode on the extensions page
 5. select `load unpacked`
 6. select the newly created folder
 7. open a new tab and allow permissions
 8. spam `ctrl + t ` !

## known bugs

 - the api sometimes is inconsistent in its responses, displaying the incorrect hourly timeline and current temperature.

## license
[MIT](https://choosealicense.com/licenses/mit/)
