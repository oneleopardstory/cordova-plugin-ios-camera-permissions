## iOS 10 Camera Permissions Plugin for Apache Cordova

**Cordova / PhoneGap Plugin Permission Settings for NSCameraUsageDescription, NSMicrophoneUsageDescription and NSPhotoLibraryUsageDescription in iOS 10 by adding a declaration to the Info.plist file**

## Install

#### Latest version from GitHub

```
cordova plugin add https://github.com/shiyating/cordova-plugin-ios-camera-permissions --save
```

## Usage

See http://cordobo.com/2269-cordova-plugin-for-nscamerausagedescription-in-ios-10/

For the changes to `plugin.xml` to take effect, you must refresh the `ios.json` file (inside the `/plugin` folder):
```
$ cordova platform rm ios
$ cordova platform add ios
```

## Platforms

Applies to iOS (10+) only.

## License

[MIT License]
