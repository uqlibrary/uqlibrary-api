uqlibrary-api
================

Web components for UQ Library API

## Configuration

uqlibrary-api elements can be used with live API and with mock data. 
baseApiUrl - base API url 
To use mock data set cookie value UQLMockData to true

### Mock files
mock files contain data in json format in same format as live API 
file names should be created based on API call with method [_get/_post/_delete], eg

API path to /account/facilities_bookings mock file should be /mock/account/facilities_bookings_get.json
API path to /facilities_availability mock file should be /mock/facilities_availability_get.json


## Testing Element



### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester). You can run them on multiple local browsers via:

```sh
npm install -g web-component-tester
wct
```

