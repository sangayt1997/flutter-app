## Flutter app tutorial for the beginner:
Please follow the below process to build your flutter app in android and ios.

### Getting Started

This project is a starting point for a Flutter application for beginner.

A few resources to get you started if this is your first Flutter project:

- [Flutter Documentation](https://flutter.dev/)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### IOS
Please follow the following steps to build your flutter app for IOS using Xcode:

1. flutter clean - to delete the /build folder and do it if necessary.
2. flutter pub get - Packages get in IntelliJ or Android Studio for the first time after adding a package.
3. flutter build ios- flutter building in ios platform.
4. Go to ios directory and pod install. (If there is no podfile found follow the 4. a step).
   a. pod init - It will generate the necessaries pod related files.
5. pod install in ios directory - install/ update all the packages for ios.
6. Then Open file Runner.xcworkspace file of your project instead of Runner.xcodeproj from the XCode.
7. Then Build your App selecting the desire simulator.

#### NOTE: Follow step 1 and 2 if you face something issues related to package while building app from Xcode.

### Android

1. Connect your devices in the laptop and Run flutter run
2. If you wish to run from android studio or not done setup with android studio. Please follow this [link](https://docs.flutter.dev/get-started/install)
