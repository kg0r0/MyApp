# MyApp
[![CircleCI](https://circleci.com/gh/kg0r0/MyApp.svg?style=svg)](https://circleci.com/gh/kg0r0/MyApp)

## Setup 

```
$ brew install watchman
$ sudo gem install cocoapods
$ npx react-native init MyApp --template react-native-template-typescript@6.3.16
(in case of glog (0.3.5) error $ sudo xcode-select --switch /Applications/Xcode.app)
$ npx react-native run-ios
$ npx react-native doctor
```

## RUN
### iOS

```
$ cd ios/
$ pod install --repo-update
$ cd ..
$ npx react-native run-ios
```
- Xcode
```
$ xed -b ios
```

## References
- https://github.com/facebook/react-native/issues/25532
- https://github.com/react-native-jp/praiser
