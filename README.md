# To-Do List  with React Native

## Requirements
- [Node](https://nodejs.org) `4.x` or newer
- [React Native](http://facebook.github.io/react-native/docs/getting-started.html) for development
- [Xcode](https://developer.apple.com/xcode/) for iOS development
- [Android Studio](https://developer.android.com/studio/index.html) for Android development
- [Android SDK](https://developer.android.com/sdk/) `23.0.2` or newer for Android development
- [Genymotion](https://www.genymotion.com/) for Android emulation
- [Android Lollipop](https://www.android.com/versions/lollipop-5-0/) or newer on your Android device to test properly
- [Firebase account](https://www.firebase.com/docs/web/guide/setup.html) `2.4.2` !!!IMPORTANT newer versions of Firebase did not support React Native at the day this app was created

See [Getting Started](https://facebook.github.io/react-native/docs/getting-started.html) to install requirement tools.

## Stack
- [React Native](https://facebook.github.io/react-native/) `0.28.0` for building native apps using react

## Demo of the Project
https://www.youtube.com/watch?v=BQAesv1gvRM&feature=youtube&app=desktop

## For Developers
### Get the source code
Clone the repo and install node components in package.json
```shell
$ git clone https://github.com/aganita/todo-with-react-native-and-firebase.git TheToDoList
$ cd TheToDoList
$ npm install
```

### Start the emulator and developent enviroment
##### iOS
```shell
$ react-native run-ios
```
##### Andorid
```shell
$ react-native run-android
```

### Debugging
[Access the in-app developer menu](https://facebook.github.io/react-native/docs/debugging.html) and select ``Debug in Chrome``.
To get to the developer menu on the ios emulator, press Control-D inside the emulator screen.  Then, turn on hot reload.

To get to the developer menu on the android emulator, just press Control-M inside the emulator screen.  Then, turn on hot reload.

### Create a release build
* Navigate to Product > Scheme > Edit Scheme... in Xcode and change Build Configuration to *Release*.
* Run in terminal :

##### iOS:
```shell
$ npm run build-ios
```
##### Android:
```shell
$ npm run build-android
```

### Issues
If you run into any issues please see the [Getting Started](http://facebook.github.io/react-native/docs/getting-started.html) guide for React Native before submitting an issue.

