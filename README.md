## Ionic-Videogular

This is a simple integration of Videogular2 with Ionic3.

Uses solution by "dbertels" to make Videogular fonts available to Ionic.  
https://forum.ionicframework.com/t/solved-ionic-and-videogular-2-scss/89454/9

Install NodeJS
https://nodejs.org/en/

Install Ionic globally.
```bash
$ npm install -g ionic cordova
```

After cloning the project, use the following command in the project folder to generate the project files.
```bash
$ npm install
```

Add Android platform to the project and run.  This will push the .apk to a device if one is plugged in and in developer mode.  Alternatively it will push to an installed emulator.  Emulators can be set up as part of Android Studio https://developer.android.com/studio/index.html
```bash
$ ionic cordova platform add android
$ ionic cordova run android
```