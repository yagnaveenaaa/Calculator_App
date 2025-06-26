# 📱 Flutter Calculator App

A **simple, cross-platform calculator app** built using **Flutter**. It supports basic arithmetic operations and runs on **Android, iOS, Web, Windows, macOS, and Linux** thanks to Flutter’s powerful cross-platform capabilities.

---

## ✨ Features

- ➕ Addition, ➖ Subtraction, ✖️ Multiplication, ➗ Division
- 🔄 Real-time result display
- 🧹 Clear (`C`) and ⌫ Backspace functionality
- 📱 Responsive & clean user interface
- 🌐 Supports mobile, web, and desktop platforms
- 💡 Beginner-friendly code and layout

---

## 🧰 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yagnaveenaaa/Calculator_App.git
cd Calculator_App

2. Install Dependencies
bash
Copy
Edit
flutter pub get

3. Run the App
bash
Copy
Edit
flutter run

Choose your preferred platform: Android emulator, iOS simulator, web browser, or desktop environment.

📦 Build APK (Android)
To build the app for Android as a release APK:

bash
Copy
Edit
flutter build apk --release
The APK file will be located at:

swift
Copy
Edit
build/app/outputs/flutter-apk/app-release.apk


📁 Project Structure
bash
Copy
Edit

Calculator_App/
├── lib/
│   ├── button_values.dart        # Calculator button labels and values
│   ├── calculator_screen.dart    # UI and interaction logic
│   └── main.dart                 # Main app entry point
├── android/                      # Android platform-specific code
├── ios/                          # iOS platform-specific code
├── linux/                        # Linux platform-specific code
├── macos/                        # macOS platform-specific code
├── windows/                      # Windows platform-specific code
├── web/                          # Web platform code
├── test/                         # Unit and widget tests
├── pubspec.yaml                  # Project dependencies and assets
├── analysis_options.yaml         # Dart analysis/linting configuration
├── .gitignore                    # Files ignored by Git
└── README.md                     # This file
🧪 Testing
Run all Flutter tests with:

bash
Copy
Edit
flutter test
📌 Notes
All code is written in Dart using the Flutter SDK

Ideal for learning stateful widgets, layout building, and UI interactions

Can be extended with features like dark mode, history, or scientific functions

👤 Author
Sree Yagna Veena

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.
