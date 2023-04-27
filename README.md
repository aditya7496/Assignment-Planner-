# Assignment-Planner-
Assignment Planner App using FLUTTER/DART
The following project was developed by a team as a project for CS 3130 at UPEI, therefore credit for works within repository are shared. The project was a 2 month build with 7 days spent on front end design and the project uses Flutter, Dart, Firebase by Google and other dependencies by Flutter.

The goal of the project is to have dedicated app that allows users to manage assignments at a University level using toolds available in general use calendars, the app is capable of being expanded with more features and functionalities to help imrpove cusotmer experience, and the design was chosen to be the most user friendly.

Team Members:

Aditya Agrawal
Kuang Xu
Yongshen Yang

Included in the App folder are the files required to run the app on VS code, or Android Studio.

Dependencies required are the follow:

Please copy below text and add to PUBSEC.YAML file and either run flutter pub get or click pub get button to download dependencies. Minor chnages in code may be required to run.

<**********************************************************************************************************************************>

name: assignment_planner

description: assignment-planner app.

# The following line prevents the package from being accidentally published to
# pub.dev using `flutter pub publish`. This is preferred for private packages.
publish_to: "none" # Remove this line if you wish to publish to pub.dev

# The following defines the version and build number for your application.
# A version number is three numbers separated by dots, like 1.2.43
# followed by an optional build number separated by a +.
# Both the version and the builder number may be overridden in flutter
# build by specifying --build-name and --build-number, respectively.
# In Android, build-name is used as versionName while build-number used as versionCode.
# Read more about Android versioning at https://developer.android.com/studio/publish/versioning
# In iOS, build-name is used as CFBundleShortVersionString while build-number used as CFBundleVersion.
# Read more about iOS versioning at
# https://developer.apple.com/library/archive/documentation/General/Reference/InfoPlistKeyReference/Articles/CoreFoundationKeys.html
version: 1.0.0+1

environment:
  sdk: ">=2.15.0 <3.0.0"

# Dependencies specify other packages that your package needs in order to work.
# To automatically upgrade your package dependencies to the latest versions
# consider running `flutter pub upgrade --major-versions`. Alternatively,
# dependencies can be manually updated by changing the version numbers below to
# the latest version available on pub.dev. To see which dependencies have newer
# versions available, run `flutter pub outdated`.
dependencies:
  flutter_login: ^4.1.1
  flutter_bloc: ^8.1.2
  flutter:
    sdk: flutter

  # The following adds the Cupertino Icons font to your application.
  # Use with the CupertinoIcons class for iOS style icons.
  cupertino_icons: ^1.0.2
  faker_dart: ^0.1.3
  equatable: ^2.0.3
  animated_splash_screen: ^1.3.0
  firebase_core: ^1.24.0
  firebase_database: ^8.1.1
  firebase_core_platform_interface: 4.5.1
  firebase_storage: ^10.3.11
  firebase_auth: ^3.11.2
  cloud_firestore: ^3.5.1
  syncfusion_flutter_calendar: ^21.1.41
  dropdown_textfield: ^1.0.8
  dropdownfield: ^1.0.3
  flutter_slidable: ^3.0.0
  flutter_datetime_picker: ^1.5.1
  flutter_svg: ^2.0.5

dev_dependencies:
  flutter_test:
    sdk: flutter

  # The "flutter_lints" package below contains a set of recommended lints to
  # encourage good coding practices. The lint set provided by the package is
  # activated in the `analysis_options.yaml` file located at the root of your
  # package. See that file for information about deactivating specific lint
  # rules and activating additional ones.
  flutter_lints: ^2.0.1

# For information on the generic Dart part of this file, see the
# following page: https://dart.dev/tools/pub/pubspec

# The following section is specific to Flutter.
flutter:
  # The following line ensures that the Material Icons font is
  # included with your application, so that you can use the icons in
  # the material Icons class.
  uses-material-design: true

  # To add assets to your application, add an assets section, like this:
  assets:
    - assets/images/undraw_schedule_re_2vro.jpg
    - assets/images/uap.png

  # An image asset can refer to one or more resolution-specific "variants", see
  # https://flutter.dev/assets-and-images/#resolution-aware.

  # For details regarding adding assets from package dependencies, see
  # https://flutter.dev/assets-and-images/#from-packages

  # To add custom fonts to your application, add a fonts section here,
  # in this "flutter" section. Each entry in this list should have a
  # "family" key with the font family name, and a "fonts" key with a
  # list giving the asset and other descriptors for the font. For
  # example:
  # fonts:
  #   - family: Schyler
  #     fonts:
  #       - asset: fonts/Schyler-Regular.ttf
  #       - asset: fonts/Schyler-Italic.ttf
  #         style: italic
  #   - family: Trajan Pro
  #     fonts:
  #       - asset: fonts/TrajanPro.ttf
  #       - asset: fonts/TrajanPro_Bold.ttf
  #         weight: 700
  #
  # For details regarding fonts from package dependencies,
  # see https://flutter.dev/custom-fonts/#from-packages
  
<*******************************************************************************************************************************>
