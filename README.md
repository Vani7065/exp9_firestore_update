# Experiment 9

## One-time Firebase setup (needed before it runs)
This experiment uses Google Cloud Firestore. The file `lib/firebase_options.dart`
is created for your own Firebase project and is not included here.

1. In Firebase console (console.firebase.google.com), create a project.
2. Turn on Firestore Database (start in test mode).
3. Install the FlutterFire CLI once:  dart pub global activate flutterfire_cli
4. In this project folder, run:       flutterfire configure
   Choose your Firebase project and Android. This creates lib/firebase_options.dart.
5. Then run:  flutter pub get  and press F5.

## Run in VS Code
1. Open this folder in VS Code (File > Open Folder).
2. Open a terminal and run:  flutter pub get
3. Pick a device (Android phone, emulator, Chrome) from the bottom-right corner.
4. Press F5 or run:  flutter run
