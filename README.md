# countryhouse

Application display list of countries, we can search through them.
after opening one country we can see 5 cards that display information from imported API.
the card contains the capital,population, currency , flag, and location on the map.
This also include APK file.

## about using app
Open project in flutter normally just check all imports carefully. 
And build the application.

important files for copying the code:-
   lib/main.dart
   lib/Screens/AllCountries.dart
   lib/Screens/Country.dart
   lib/Screens/countryMap.dart
   pubspec.yaml (for dependencies)
   
## about using app
errors:-
google map import may not work if the key expired. for that please enter your key in

android/app/src/main/AndroidManifest.xml

### here

 <application	 
  android:name="io.flutter.app.FlutterApplication"	 
  android:label="country_house"	 
  android:icon="@mipmap/ic_launcher">	 
  <meta-data android:name="com.google.android.geo.API_KEY"	 
  #### android:value="AIzaSyAsWan8XuW-z8OCw7dd2Gnwe3ICBqVA-jg"/>





## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


