# Flutter Calculator App

A simple calculator app built using Flutter. It supports basic arithmetic operations and runs on Android, iOS, web, Windows, macOS, and Linux using Flutter’s cross-platform capabilities.

## ✨ Features

- Addition, subtraction, multiplication, division
- Real-time result display
- Clear (C) and backspace (⌫) functionality
- Cross-platform support (mobile, web, desktop)
- Clean and responsive UI

## 📁 Project Structure

Calculator_App/
├── lib/
│ ├── button_values.dart # Button labels and logic mapping
│ ├── calculator_screen.dart # UI layout and button handling
│ └── main.dart # App entry point
├── android/ # Android platform code
├── ios/ # iOS platform code
├── linux/ # Linux platform code
├── macos/ # macOS platform code
├── windows/ # Windows platform code
├── web/ # Web platform code
├── test/ # Unit tests
├── pubspec.yaml # Dependencies and assets
├── pubspec.lock # Locked package versions
├── analysis_options.yaml # Linting rules
├── .gitignore # Git ignore settings
├── .metadata # Flutter metadata
└── README.md # Project documentation

markdown
Copy
Edit

## 🚀 Getting Started

### Prerequisites

- Flutter SDK installed  
  ([Install Flutter](https://docs.flutter.dev/get-started/install))
- Code editor like VS Code or Android Studio

### Running the App

```bash
flutter pub get
flutter run
You can select a device or target like Android emulator, Chrome (for web), or desktop.

Build APK (for Android)
bash
Copy
Edit
flutter build apk --release
The APK will be generated at:

swift
Copy
Edit
build/app/outputs/flutter-apk/app-release.apk

📌 Notes
All code is written in Dart using Flutter SDK.

This project is suitable for learning, showcasing Flutter UI, or as a base for more advanced calculators.

👤 Author
Sree Yagna Veena
