# React Native Web Starter

## Introduction

This repo is intending to provide an easy starting point for developers looking to make fully cross platform applications across both web with [React Native Web](https://github.com/necolas/react-native-web) and mobile with [Expo](https://github.com/react-community/create-react-native-app).

All branches represent a particular starting point.

It is bootstrapped with [Create React App](https://github.com/facebook/create-react-app) so you can run `yarn web` in order to start up the development web server with all the hot reloading goodness you've come to expect.

It has then been integrated with [Create React Native App](https://github.com/react-community/create-react-native-app) and running `yarn ios` or `yarn android` will start the Expo packager. You can also run the project from the Expo XDE program.

## Branches

| Branch                  | Description                                                                                                                                                              |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| master                  | The most minimal possible boilerplate, will always be the case                                                                                                           |
| redux                   | Implements redux reducers, actions, store and connection including example                                                                                               |
| navigation-react-router | Using react-router-dom, react-router-native and react-router-navigation in order to have a platform agnostic navigation solution including native look at feel on phones |
| typescript              | Uses the TypeScript compiler with command `yarn watch` to track file changes and compile on the fly for stronger typed RNW code                                          |

## Get Started

Clone the branch with the starting point you want and just rename the project (don't forget the `package.json`, Run `git remote rm origin && yarn` to remove the ref to this repo and install node_modules then you're good to go. 🙂

A full list of the scripts defined in `package.json` is shown below.

| Script              | Action                                                  |
| ------------------- | ------------------------------------------------------- |
| `yarn web`          | Start CRA Development Build                             |
| `yarn build-web`    | Create production build for web                         |
| `yarn eject-web`    | Eject from CRA                                          |
| `yarn start-native` | Start the Expo packager                                 |
| `yarn eject-native` | Eject from Expo                                         |
| `yarn android`      | Start expo packager and install app to Android Emulator |
| `yarn ios`          | Start expo packager and install app to iOS Simulator    |
| `yarn test-native`  | Run testing script for mobile app                       |
| `yarn test-web`     | Run testing script for web app                          |
| `yarn test`         | Run both testing scripts                                |

### Future Plans for this Library

The aim for this library is to make several branches that have different starting points i.e. Navigation, Auth etc.

Master branch will always be the most minimal starting point.
