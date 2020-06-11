# Polls app

This is a an application that lets users vote through the [Polls API](https://pollsapi.docs.apiary.io/).

The project uses:

- [React Native](https://facebook.github.io/react-native/docs/getting-started) for iOS & Android app development
- [TypeScript](https://www.typescriptlang.org/docs/home.html) for type-safety
- [Redux](https://redux.js.org/api/api-reference) for state management
- [Sagas](https://redux-saga.js.org/) for managing side effects
- [React Native Testing Library](https://callstack.github.io/react-native-testing-library/) for testing the components

## Supported features

| Pagination                         |           Voting           |             Creating questions |
| ---------------------------------- | :------------------------: | -----------------------------: |
| ![pagination](demo/pagination.gif) | ![voting](demo/voting.gif) | ![creating](demo/creating.gif) |

## Running

Install dependencies:

```
yarn

cd ios && pod install
```

Start packager:

```
yarn start
```

### iOS:

Run the app:

```
yarn ios
```

If you prefer Xcode rather than command line:

- open `./ios/PollsApp.xcworkspace` in Xcode
- select a simulator or a device
- hit the Run button

### Android:

Have an Android emulator running (quickest way to get started), or a device connected

Run the app:

```
yarn android
```
