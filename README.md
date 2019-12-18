# Unsplash Image View Search

### Install Instructions

#### Android

    yarn
    npm run android

#### IOS

    yarn
    cd ios
    pod install
    npm run ios

#### File structure

The file structure is inspired by the Atomic File Struction for React [Read Here](https://medium.com/@janelle.wg/atomic-design-pattern-how-to-structure-your-react-application-2bb4d9ca5f97).
The structure was adapted for React Native. This means that Organisms has been replaced with scences.

### Features

- The api request is delayed after 1000ms after you stopped typing. This so that I don't spam the api with unnecessary requests
- Written with React 16.8+ React Hooks

### Android

![Running on android](resources/androidGif.gif)

### IOS

![Running on android](resources/iosGif.gif)
