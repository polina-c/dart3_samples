# Dart 3 samples

A sample project with records, patterns, and sealed classes enabled.

## Usage

Switch to the Flutter SDK's main channel:

```
flutter channel main
flutter upgrade
```

Get dependencies:

```
dart pub get
```

Samples are in the `bin/` directory. To run, you must include the experiment
flags:

```
dart run --enable-experiment=records,patterns bin/records.dart 
```
