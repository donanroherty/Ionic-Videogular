## How to

Install NodeJS
https://nodejs.org/en/

Install Ionic globally
```bash
$ npm install -g ionic cordova
```

After cloning the project, use the following command in the project folder to generate the project files.
```bash
$ npm install
$ ionic state restore
```

Add Android platform to the project and run.  This will push the .apk to a device if on is plugged in and in developer mode.  Alternativly it will push to an installed emulator.  Emulators can be set up as part of Android Studio https://developer.android.com/studio/index.html
```bash
$ ionic cordova platform add android
$ ionic cordova run android
```