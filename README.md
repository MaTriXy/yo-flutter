# Yo! In Flutter.

Basically Yo! written in Flutter. Done in a three hour workshop with people who never used Flutter before 🍻

## How to run the app

> Are you in a hurry and just want to check out the end-result on your phone? In the releases tab you will find a precompiled APK to download 🚀

If you would like to compile the code and run the app on your machine, you will have to create a new Firebase project and make sure to add the following files:

`ios/Runner/GoogleService-Info.plist`

`android/app/google-services.json`  

Add the SHA-1 of your local certificate to Firebase when you register the Android app in order to make the Google Sign-In work.

On iOS you need to edit `ios/Runner/Info.plist` and paste in your `REVERSED_CLIENT_ID`.

Last but not least you will have to deploy the Cloud Function inside the `firebase` folder and replace the URL inside the `home_page.dart` file. And voilà, you are all set!

## Disclaimer

Please note that this code is not production ready, it should just show how quick you could build a million dollar app for Android and iOS 😉
