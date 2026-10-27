# AIShapers

<p align="center">
  <strong>A Cross-Platform Flutter Application</strong>
  <br />
  Developed for the AI Shaper Hackathon
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Platform-Cross--Platform-6366F1?style=for-the-badge" alt="Cross-platform" />
</p>

---

## Overview

**AIShapers** is a Flutter application developed as part of the AI Shaper Hackathon.

Built with Flutter and Dart, the project provides a foundation for a cross-platform application, with platform-specific project directories for Android, iOS, web, Windows, macOS, and Linux.

## Tech Stack

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform application framework |
| Dart | Application programming language |
| Android | Mobile application platform |
| iOS | Mobile application platform |
| Web | Browser-based application target |
| Windows, macOS, Linux | Desktop platform project targets |

## Project Structure

```text
AIShapers/
├── android/              # Android platform configuration
├── ios/                  # iOS platform configuration
├── linux/                # Linux platform configuration
├── macos/                # macOS platform configuration
├── windows/              # Windows platform configuration
├── web/                  # Web platform assets and configuration
├── lib/                  # Main Dart application code
├── test/                 # Application tests
├── assets/                # Project assets
├── pubspec.yaml           # Dependencies and project configuration
├── pubspec.lock           # Locked dependency versions
└── analysis_options.yaml  # Dart static analysis rules
```

## Getting Started

### Prerequisites

Install the following tools:

- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- [Dart SDK](https://dart.dev/get-dart) (included with Flutter)
- [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/)
- A configured emulator, simulator, browser, or supported physical device

Verify your Flutter installation:

```bash
flutter doctor
```

### Installation

Clone the repository:

```bash
git clone https://github.com/AIShaperHackathon/AIShapers.git
cd AIShapers
```

Install project dependencies:

```bash
flutter pub get
```

### Run the Application

Start the application on a connected device or emulator:

```bash
flutter run
```

To list available devices:

```bash
flutter devices
```

To run the web version, if web support is enabled in the local Flutter installation:

```bash
flutter run -d chrome
```

### Run Tests

Execute the project's automated tests:

```bash
flutter test
```

### Build for Release

Build an Android APK:

```bash
flutter build apk --release
```

Build the web application:

```bash
flutter build web
```

Build commands require the corresponding platform tooling and configuration.

## Development

1. Implement application screens and logic in `lib/`.
2. Add required packages through `pubspec.yaml`.
3. Keep platform-specific configuration within the relevant platform directories.
4. Add automated tests under `test/`.
5. Run `flutter analyze` and `flutter test` before submitting changes.

## Contributing

Contributions and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes with a descriptive message.
4. Open a pull request for review.

## License

Refer to the repository for licensing information.

---

<p align="center">
  Built with Flutter for the AI Shaper Hackathon.
</p>
