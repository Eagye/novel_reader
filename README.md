# Novel Reader

A smart Flutter reading application that helps users understand complex literature by explaining and highlighting pages with difficult meanings, breaking them down for proper understanding.

## Features

- **EPUB Reader**: Full-featured EPUB viewing with text highlighting, search, and chapter navigation
- **Intelligent Text Analysis**: Automatically identifies and highlights complex or difficult passages
- **Detailed Explanations**: Provides breakdowns and explanations of challenging content
- **Enhanced Reading Experience**: Makes difficult literature more accessible and understandable
- **Cross-Platform**: Built with Flutter for iOS, Android, and Web

## Project Description

Novel Reader is designed to assist readers in comprehending complex texts by:
- Highlighting pages and passages with difficult meanings
- Breaking down complex sentences and concepts
- Providing clear explanations to improve understanding
- Making literature more accessible to all readers

## Getting Started

### Prerequisites

- Flutter SDK (latest stable version)
- Dart SDK (comes with Flutter)
- Android Studio / Xcode (for mobile development)
- VS Code or Android Studio (recommended IDEs)

### Dependencies

This project uses the following key packages:

- **flutter_epub_viewer**: ^1.2.2 - Full-featured EPUB document viewer with text highlighting, search functionality, chapter listing, and customizable UI
  - Supports loading EPUBs from files, URLs, or assets
  - Provides reading progress tracking with CFI (Canonical Fragment Identifier)
  - Customizable display settings and touch interactions

For complete dependency list, see `pubspec.yaml`.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Eagye/novel_reader.git
cd novel_reader
```

2. Install dependencies:
```bash
flutter pub get
```

3. Platform-specific setup:
   - **Android**: Cleartext traffic is already enabled in `AndroidManifest.xml` (required for EPUB viewer)
   - **iOS**: May require additional permissions in `Info.plist` depending on your EPUB source

4. Run the app:
```bash
flutter run
```

### Building

- **Android**: `flutter build apk` or `flutter build appbundle`
- **iOS**: `flutter build ios`
- **Web**: `flutter build web`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

(To be added)

## Author

(To be added)

