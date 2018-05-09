# novonity-plugin-ios-permissions
This plugin prevents crashes in iOS apps due to missing entries in the plist file.

# Why?
File inputs suddenly didn't work in iOS applications created using PhoneGap Build. When clicking on a file input and trying to select an image, the application crashes. This plugin adds NSCameraUsageDescription and NSPhotoLibraryUsageDescription and so on to our application.

# Usage
Include this plugin in your config.xml:
```
cordova plugin add novonity-plugin-ios-permissions
```

# Note
Maybe, this bug has already been fixed on PGB (or the platform you are using). Only add this plugin if you experience crashes after clicking on the file input like described above.

**Please note that this plugin is experimental.**
