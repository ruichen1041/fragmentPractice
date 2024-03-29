fragmentPractice
============================
An implemented practice code to get familiar with the fragment usage in the Android Studio.
Followed instructions can be found here: https://developer.android.com/codelabs/kotlin-android-training-create-and-add-fragment?index=..%2F..android-kotlin-fundamentals#8

App Introduction
------------

The AndroidTrivia app asks the user trivia questions about Android development.
It makes use of the navigation component within Jetpack to move the user between
screens. Each screen is implemented as a fragment.

The app navigates using buttons, the app bar, and a navigation drawer. Because
students haven't yet learned about saving data or the Android lifecycle, the app
tries to eliminate bugs caused by configuration changes.

Implemented features
------------

The TitleFragment screen has a Rules and About button as shown below.
When the user taps the Rules or About button, the app navigates to the RulesFragment or AboutFragment, as appropriate

The RulesFragment and AboutFragment screens both have a Play button that navigates to the GameFragment

When clicking the system Back button at the bottom of the screen on Rules page and About page, the app navigates back to the title Fragment, not to the rules Fragment or the about Fragment.


Key feature showcase
============================
Title page
------------
<img src="./demoFigure/showcase_titlePage.png" width="200">

About page
------------
<img src="./demoFigure/showcase_aboutPage.png" width="200">

Rules page
------------
<img src="./demoFigure/showcase_rulesPage.png" width="200">
