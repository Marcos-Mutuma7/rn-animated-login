# RN Animated Login

React Native Expo starter app that adds a Login/Registration UI (not yet connected to back end) with an animated logo tied to keyboard appearance.

Custom assets include the images in the ```components/Logo/images``` folder and the ```src/assets/images/splash.png``` file. The app is currently customized as a mock Twitter brand called **tweetster**.

### Initialized with **[Create React Native App](https://github.com/react-community/create-react-native-app)**

__CRNA Documentation Follows:__

## Quick Overview

Make sure you have Node v6 or later installed. No Xcode or Android Studio installation is required.

```sh
$ clone repo
$ cd rn-animated-login
$ npm start
```

The `npm start` command starts the Expo CLI server. You can now run the project on your phone by using the Expo app.

### Android

- Install the [Expo](https://expo.io) app on your Android device.
- Scan the QR code in your terminal from the Expo app to run the project on your phone.
- Alternatively you can press 's' in the terminal and sign in with an Expo account, and sign in with the same account in the Expo app: your projects will automatically appear in the "Projects" tab.

### iOS

- Install the [Expo](https://expo.io) app on your iOS device.
- Press 'e' in the terminal to send the app link to your email address or phone number. This link can be used to run your project from the Expo app.
- Alternatively you can press 's' in the terminal and sign in with an Expo account, and sign in with the same account in the Expo app: your projects will automatically appear in the "Projects" tab.

Expo CLI allows you to work with all of the [Components and APIs](https://facebook.github.io/react-native/docs/getting-started.html) in React Native, as well as the [JavaScript APIs](https://docs.expo.io/versions/latest/sdk/index.html) that the Expo app provides.


### Or, without cloning the repo, demo the app with IOS/Android by scanning below barcode after having installed Expo app (Expo will run the app in development mode):
![barcode for expo app](https://user-images.githubusercontent.com/3064557/56553147-7623d580-655b-11e9-8fa7-001005020225.png)

## Sections

- [Getting Started](#getting-started)
- [Philosophy](#philosophy)
- [Support and Contact](#support-and-contact)
- [FAQs](#faqs)
- [Contributing](#contributing)

## Getting Started on Development

#### `npm start`

Runs the app in development mode with an interactive prompt. To run it without a prompt, use the `--no-interactive` flag.

Open it in the [Expo app](https://expo.io) on your phone to view it. It will reload if you save edits to your files, and you will see build errors and logs in the terminal.

#### `npm test`

Runs the [jest](https://github.com/facebook/jest) test runner on your tests.

#### `npm run ios`

Like `npm start`, but also attempts to open the app in the iOS Simulator if you're on a Mac and have it installed.

#### `npm run android`

Like `npm start`, but also attempts to open the app on a connected Android device or emulator. Requires an installation of Android build tools (see [React Native docs](https://facebook.github.io/react-native/docs/getting-started.html) for detailed setup).

#### `npm run eject`

This will start the process of "ejecting" from Create React Native App's build scripts. You'll be asked a couple of questions about how you'd like to build your project.

**Warning:** Running eject is a **permanent** action. Please use a version control system, such as git, so you can revert back if necessary. An ejected app will require you to have an [Xcode and/or Android Studio environment](https://facebook.github.io/react-native/docs/getting-started.html) set up.

## Philosophy

- **Minimal "Time to Hello World"**: Create React Native App should reduce the setup time it takes to try building a mobile app to the absolute minimum, ideally on par with React web development (especially as seen with [Create React App](https://github.com/facebookincubator/create-react-app)).
- **Develop on Your Device**: It should be easy to develop on a physical device when you want to test how your app feels and responds to inputs.
- **One Build Tool**: If you just want to get started with React Native, you shouldn't need to install Xcode, Android Studio, NDKs, or mess with environment variables.
- **No Lock-In**: You can always "eject" to your own build setup if you need to write custom native code or modify how your app is built.

## Support and Contact

If you're having issues with Create React Native App, please make sure:

- The issue is not covered in the [Expo Docs](https://docs.expo.io/versions/latest/)
- There is not already an [open issue](https://github.com/expo/expo-cli/issues) for your particular problem

If you've checked the documentation and currently open issues, please either [open a new GitHub issue](https://github.com/expo/expo-cli/issues/new) or ask a question on [Expo forums](https://forums.expo.io/c/help). **Please do not DM or email project maintainers directly**, as it's very important that support takes place in public locations where others can benefit from the conversation.

## FAQs

### What API specification should I be looking at while developing?

Apps made with Create React Native App support everything in the Components and APIs sections of the [React Native Documentation](https://facebook.github.io/react-native/docs/getting-started.html).

Apps made with Create React Native App also support most of the JavaScript-to-Native APIs provided by the [Expo SDK](https://docs.expo.io/versions/latest/sdk/index.html), since they are loaded by the Expo app.

### What are the limitations of Create React Native App?

The main limitation of a Create React Native App project is that it must be written in pure JavaScript and not have any dependencies which rely on custom native code (i.e. ones which require running `react-native link` to work). This allows the projects to load directly on a phone without native compilation, and also means that it's not necessary to install or use Android Studio or Xcode.

### What if I want to write custom native code for my app?

If you're sure that you need custom native code, please read the [ejecting guide](https://github.com/react-community/create-react-native-app/blob/master/EJECTING.md).

### How do I get my app into the Play Store/App Store?

If you need to build IPAs and APKs for publishing to the App Store and/or Play Store, you can either eject (see above guide) and build them yourself using Xcode and Android Studio, or you can use a service like [Expo's standalone app builds](https://docs.expo.io/versions/latest/guides/building-standalone-apps.html) to publish your pure JS app.

## Contributing

From version v2.0.1, Create React Native App has been merged with Expo CLI.

Please see [Contributin to Expo CLI](https://github.com/expo/expo-cli/blob/master/CONTRIBUTING.md) in the Expo CLI monorepo for instructions on contributing to Expo CLI.

## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/react-community/create-react-native-app/graphs/contributors"><img src="https://opencollective.com/create-react-native-app/contributors.svg?width=890&button=false" /></a>

## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/create-react-native-app#backer)]

<a href="https://opencollective.com/create-react-native-app#backers" target="_blank"><img src="https://opencollective.com/create-react-native-app/backers.svg?width=890"></a>

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/create-react-native-app#sponsor)]

<a href="https://opencollective.com/create-react-native-app/sponsor/0/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/1/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/2/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/3/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/4/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/5/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/6/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/7/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/8/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/create-react-native-app/sponsor/9/website" target="_blank"><img src="https://opencollective.com/create-react-native-app/sponsor/9/avatar.svg"></a>
