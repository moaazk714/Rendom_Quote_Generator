# Daily Spark

Daily Spark is a Flutter quote app for discovering inspiration, curating favorite quotes, and saving personal quotes on-device.

## Features

- Browse a curated collection of quotes with author and category details.
- Generate quotes, copy them, and save or remove favorites.
- Filter favorites by category.
- Create, search, and delete custom quotes.
- Use the mindful reflection breathing timer.
- Persist custom quotes and favorites locally with SharedPreferences.

## Getting started

1. Install the Flutter SDK compatible with the Dart constraint in `pubspec.yaml`.
2. Fetch dependencies with `flutter pub get`.
3. Run the app with `flutter run`.
4. Run static analysis and tests with `flutter analyze` and `flutter test`.

Google Fonts are loaded by the `google_fonts` package; internet access may be needed the first time each font is used unless the fonts are bundled for offline use.

## Release checklist

- Configure production Android signing before distributing an Android release. The current Android release build type uses the debug signing configuration.
- Set up a valid iOS signing team and provisioning profile in Xcode before distributing an iOS build.
- Review app identifiers, icons, store metadata, and the quote catalog and its attribution before publishing.
