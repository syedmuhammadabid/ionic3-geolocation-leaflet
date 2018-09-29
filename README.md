# ionic3-geolocation-leaflet

This repository is about Geolocation using leaflet and google places API implemented on ionic 3.


### Tech

This project uses a number of open source projects to work properly:

* [Ionic](https://ionicframework.com)
* [Leaflet](https://leafletjs.com/)
* [Google Places API](https://developers.google.com/places/web-service/intro)

And of course this itself is open source with a [public repository](https://github.com/syedmuhammadabid/ionic3-geolocation-leaflet)
 on GitHub.

### Installation
This requires [Node.js](https://nodejs.org/) v4+ to run.

Install the prerequisites.
```sh
$ npm install -g ionic
```
Once ionic framework is installed then,
```sh
$ git clone https://github.com/syedmuhammadabid/ionic3-geolocation-leaflet
$ cd ionic3-geolocation-leaflet
$ npm install
```
Open project folder and then `src/index.html`, in index.html provide Google Places API [key](https://developers.google.com/places/web-service/get-api-key),
```sh
 <!-- Google Places API -->
  <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_API_KEY&libraries=places"></script>
```
and now just run,
```sh
$ ionic serve
```
### Development

Want to contribute? Great!
