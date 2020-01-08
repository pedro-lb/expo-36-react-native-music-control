# expo-36-react-native-music-control
Attempt to make react-native-music-control work with Expo ejected app (ExpoKit) in SDK 36.

After cloning:
`yarn install`

Run it with:
`expo start`

Expected behaviour:
![Error](https://i.imgur.com/Zg9OK1K.png)


# Steps to reproduce:
Init expo app:
`expo init <app>` - blank or whatever

Eject to ExpoKit:
`expo eject`- use ExpoKit

Add react-native-music-control:
`expo install react-native-music-control` OR `yarn add react-native-music-control`

Link library:
`react-native link react-native-music-control`

Add permissions:
Add `<uses-permission android:name="android.permission.FOREGROUND_SERVICE" />` to `AndroidManifest.xml`

Add import to App.js: 
`import MusicControl from 'react-native-music-control';`

Run:
`yarn start`

Error :(
