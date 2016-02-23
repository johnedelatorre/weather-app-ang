Weather-app uses:
* [Yeoman Web App Bootstrap]
* [AngularJS v1.2.0-rc.2](https://github.com/angular/angular.js) / [angular-seed](https://github.com/angular/angular-seed)
* [iso-3166-country-codes-angular](https://github.com/BluePyth/iso-3166-country-codes-angular)
* [Bootstrap v3.0.0](https://github.com/twbs/bootstrap)


## Installation

```
Download
$ cd [directory]
$ npm install
$ bower install
$ npm start 
Points to Browser > http://localhost:8000/app/index.html

Demo of working app: http://www.uppereastsidewebguy.com/jdweather-angular/app/index.html
```
Partials:
- Forecast
- Storm Forecast
- Wind Forecast

Locations:
- In Services.js
  > API Key (Mandatory)
  > City Names

Templates Engine:
- Directives
  > Pulls in weather icons
  > Weather Panel Partials

  Modules Used:
  'ngRoute',
  'openWeatherApp.filters',
  'openWeatherApp.services',
  'openWeatherApp.directives',
  'openWeatherApp.controllers',
  "iso-3166-country-codes"
