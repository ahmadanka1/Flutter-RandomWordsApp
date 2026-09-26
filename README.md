# Flutter Word Pair Generator

A simple Flutter application that generates random English word pairs and allows users to save their favorite combinations.

This project was built to practice fundamental **Flutter and Dart concepts**, including state management, widgets, lists, navigation, and third-party packages.

## Features

* 🔤 Generates random English word pairs
* 📜 Infinite scrolling list of word pairs
* ❤️ Save and remove favorite word pairs
* 📋 View all saved word pairs on a separate screen
* 🎨 Simple Material Design interface
* ⚡ Lightweight Flutter application

## Technologies Used

* **Flutter**
* **Dart**
* **Material Design**
* **english_words** package

## How It Works

The application uses the `english_words` package to generate random combinations of English words.

Users can:

1. Scroll through the generated word pairs.
2. Tap a word pair to add or remove it from their favorites.
3. Open the saved-word-pairs screen using the list icon in the app bar.
4. View all their saved combinations.

The application keeps the generated and saved word pairs in memory using Dart collections and Flutter's `setState()` for UI updates.

## Project Structure

```text
lib/
├── main.dart
└── random_words.dart
```

### `main.dart`

Initializes the Flutter application and sets up the main `MaterialApp` and theme.

### `random_words.dart`

Contains the main `RandomWords` widget and handles:

* Word-pair generation
* Displaying the scrolling list
* Saving and removing favorites
* Navigation to the saved word-pairs screen

## Getting Started

### Prerequisites

Make sure you have installed:

* [Flutter](https://flutter.dev/)
* Dart SDK
* Android Studio, VS Code, or another Flutter-compatible IDE

### Installation

Clone the repository:

```bash
git clone https://github.com/ahmadanka1/flutter-word-pair-generator.git
```

Navigate to the project directory:

```bash
cd flutter-word-pair-generator
```

Install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

## Dependencies

The main external dependency used by this project is:

```yaml
dependencies:
  flutter:
    sdk: flutter
  english_words: ^4.0.0
```

## Learning Objectives

This project demonstrates practical use of:

* Flutter `StatelessWidget` and `StatefulWidget`
* Widget composition
* `ListView.builder`
* `ListTile`
* `Navigator` and page navigation
* `setState()` for state management
* Dart `List` and `Set`
* The `english_words` package
* Material Design components

## Screens

### Word Pair Generator

The main screen displays randomly generated English word pairs. Users can tap a word pair to save it.

### Saved Word Pairs

The saved items can be accessed through the list icon in the top-right corner of the application.

## Future Improvements

Possible improvements include:

* Persistent storage for saved word pairs
* Search and filtering
* Ability to remove all saved pairs
* Custom themes and dark mode
* Animations and improved UI
* Unit and widget tests

## License

This project was created for learning and portfolio purposes.
