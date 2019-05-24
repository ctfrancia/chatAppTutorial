#  Create a functioning  chat app using Angular 7, Ionic 4, Cordova, Socket.io, Redis, Express

[github](https://github.com/ctfrancia/chatAppTutorial) if you want to see the code

## What this is



## Pre-requisites

1. Angular installed
2. Ionic installed
3. Node

### Packages needed

1. `$ npm i Ngx-socket-io express `
2. `$ npm i -g nodemon`

## Getting Started

1. follow [Ionic 4](https://ionicframework.com/getting-started#cli) getting started, pretty straight forward, for this example I am going to use `$ ionic start chatApp tabs`, I answered 'no' to the dev app thing.
2.  `$ mkdir server`

You should now have what looks like this in your folder

- chatApp
- server
- README.md

Now let's get prepared for the native side of things. Let's start by going over to the [docs](https://ionicframework.com/docs/installation/android) of Ionic to set up the Android environment, I recommend this because iOS is more difficult.

Alright now you are all set and ready to start your app for the first time! Make sure you have your phone connected to your laptop and phone is set to [Development Mode](http://bfy.tw/NoN9) and type:

1. `$ ionic cordova build android`
2. `$ ionic cordova run android --device --livereload`

