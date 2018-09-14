# react-native-boilerplate
A React Native Template


All you need to do is to make sure you have android studio installed with `ADB`driver.

Clone the repo
```
git clone https://github.com/e55o/react-native-boilerplate.git
```

Then perform an 
```
npm install
```

Then Go to your React native Project -> Android
Create a file `local.properties`
Open the file
paste the SDK path

in Windows `sdk.dir = C:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk`
in macOS `sdk.dir = /Users/USERNAME/Library/Android/sdk`
in linux `sdk.dir = /home/USERNAME/Android/Sdk`
Replace `USERNAME` with your user name

after that run it for android/ios using
```
react-native run-android
```
OR
```
react-native run-ios
```

Make sure you connect your mobile device and set the `USB Debugging Mode` to ON, and your app will load on the phone

Happy Coding! :tada::tada:
