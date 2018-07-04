# BLOC Pattern Login Form

A login form with validation created with Flutter.

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

## About the app

- This form and validation functions are created by using the BLOC pattern with RxDart instead of using StatefulWidget

## This app covers the following concepts from flutter, Dart and RxDart:

- BLOC pattern to share information/state in the app between different sections/screens
- Concept of _Single Global Instance_ BLOC and _Scoped Instance_ BLOC based on the scale of the app
- Single Global Instance: Single source of truth of your app state
- Scoped Instance: Multiple sources of truth divided based on sections/screens of the app
- StreamBuilder Widget to access streams/methods in the Bloc from another Widget
- Intro to RxDart for additional functionalities on Stream and StreamController
- Dart(Stream) => RxDart(Observable), Dart(StreamController) => RxDart(Subject)
- Using RxDart Observable to merge streams as one for form submission
- Concept of _Single-Subscription Stream_ and _Broadcast Stream_
- Intro to BehaviorSubject to replace StreamController.broadcast for additional function to go back in time to retrieve the latest stream values for form submission
- Best practice on adding _dispose_ function in Bloc class for the ability to close streams (or IDE might complain with warning)
- Best practice on setting StreamController as _private_ instance method to avoid confusion from newcomers working on the same project
