# Creating real cross-platform applications with Angular, Cordova & Electron

This sample was built for the [Hamburg AngularJS Meetup](https://www.meetup.com/Hamburg-AngularJS-Meetup/events/234414340/) and was _forked_ from [here](https://github.com/thinktecture/windows-developer-cross-platform-article-series).
Slides for the talk are on [Speaker Deck](https://speakerdeck.com/manuelrauber/creating-real-cross-platform-applications-with-angular-cordova-and-electron).

## Setup

* Run `npm i` to install all dependencies

## Scripts

* `npm start`: Development server on `http://localhost:4200`
* `npm run hmr`: Development server on `http://localhost:4200` with HMR enabled
* `npm run build`: Creates a development build
* `npm run build-prod`: Creates a production build
* `npm run build-desktop`: Creates an electron desktop build for all available platforms
* `npm run build-mobile`: Create a cordova mobile build for Android, iOS and Windows
  * `npm run build-mobile-android`: Builds only for Android
  * `npm run build-mobile-ios`: Builds only for iOS
  * `npm run build-mobile-windows`: Builds only for Windows
