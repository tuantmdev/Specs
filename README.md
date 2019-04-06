## Carthage specifications

![](Images/header.png)
There are some great frameworks out there, but unfortunately not all of them offer Carthage support. Luckily there is an easy workaround to include raw frameworks in your project. It works by hosting a JSON file that provides a mapping between the versions and the matching urls of the framework. After that, all you have to do is to refer to that JSON url in your Cartfile.

### Supported Frameworks

#### Crashlytics
Powerful, yet lightweight crash reporting solution (requires the Fabric framework).
Website: https://fabric.io/kits/ios/crashlytics

##### Add to Cartfile

```
binary "https://tuantmdev.github.io/Specs/Carthage/iOS/Crashlytics.json"
binary "https://tuantmdev.github.io/Specs/Carthage/iOS/Fabric.json"
```
