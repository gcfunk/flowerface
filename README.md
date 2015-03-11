# flowerface

An app created with PhoneGap http://phonegap.com/

http://docs.phonegap.com/en/edge/guide_platforms_index.md.html

http://plugins.cordova.io/#/

For now, working on android, ios, and browser platforms

# Getting Started

http://phonegap.com/install/

I didn't actually create the app with the phone gap command.  I did that with the cordova command (See http://docs.phonegap.com/en/edge/guide_cli_index.md.html#The%20Command-Line%20Interface)

# Android notes

http://docs.phonegap.com/en/edge/guide_platforms_android_index.md.html#Android%20Platform%20Guide

    cordova platform add android
    cordova build android
    cordova emulate android
    cordova run android

I needed to:

* download and install Android Studio from http://developer.android.com/sdk/index.html which has the sdk in it.
* put the sdk in my PATH in ~/.bash_profile
* install ant via brew `brew install ant`

# Browser notes

There isn't a platform guide for browser

    cordova platform add browser
    cordova build browser
    cordova run browser

# IOS notes

http://docs.phonegap.com/en/edge/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide

    cordova build ios
    cordova emulate ios

I needed to:

* Install xcode (but not the command line tools like the phonegap platform guide says)
* `npm install -g ios-sim`
