## SetUP

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
$ npx native run-ios
```
- Xcode
```
$ xed -b ios
```

## References
- https://github.com/facebook/react-native/issues/25532