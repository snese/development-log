# [Homebrew](http://brew.sh/)
```shell
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
# [npm](https://www.npmjs.com/)
```shell
brew install npm
```
# [Cordova](https://cordova.apache.org/)
## Install
```shell
sudo npm install -g cordova
```
## Create
```shell
cordova create hello com.example.hello HelloWorld
```
## Add Platform
Enter into project folder first
```shell
cordova platform add ios
```
## Build
By default, the cordova create script generates a skeletal web-based application whose home page is the project's www/index.html file. Edit this application however you want, but any initialization should be specified as part of the [deviceready](https://cordova.apache.org/docs/en/5.0.0/cordova_events_events.md.html#deviceready) event handler, referenced by default from www/js/index.js.

Run the following command to iteratively build the project:
```shell
cordova build
```
This generates platform-specific code within the project's platforms subdirectory. You can optionally limit the scope of each build to specific platforms:
```shell
cordova build ios
```
The cordova build command is a shorthand for the following, which in this example is also targeted to a single platform:
```shell
cordova prepare ios
cordova compile ios
```
In this case, once you run prepare, you can use Apple's Xcode SDK as an alternative to modify and compile the platform-specific code that Cordova generates within platforms/ios. You can use the same approach with other platforms' SDKs.
# [Bower](http://bower.io/)
```shell
sudo npm install -g bower
```
# [Mobile Angular UI](http://mobileangularui.com/)
```shell
sudo npm imstall -g mobile-angular-ui
```
# [Videogular](http://www.videogular.com/)
```shell
bower install videogular
```

- Recommend:
```shell
bower install videogular-themes-default
```

```shell
bower install videogular-controls
 
bower install videogular-buffering
 
bower install videogular-overlay-play
 
bower install videogular-poster
 
bower install videogular-ima-ads
 
bower install videogular-angulartics
```

```shell
bower install angular

bower install angular-sanitize
```

# Simple httpd server
```shell
python -m SimpleHTTPServer 8080
```
