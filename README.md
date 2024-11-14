# Data structure projects

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Localization](#localization)
- [Theming](#theming)
- [Contributors](#contributors)

## Overview
This is a Data Structures project built using python, which includes implementations of basic data structures such as arrays, stacks, queues, and trees. Each data structure comes with essential operations and is integrated with a simple GUI for easy interaction and visualization.


## Features
- **Array Operations**: Create, read, update, and delete elements from an array.
- **Stack Operations**: Push, pop, peek, and check if the stack is empty.
- **Queue Operations**: Enqueue, dequeue, and check if the queue is empty.
- **Tree Operations**: Insert, delete, traverse (in-order, pre-order, post-order).
- **GUI**: Simple graphical user interface for interacting with the data structures.

## Getting Started

### Prerequisites
:
Ensure you have the following installed before running this project:
- python SDK
- IDE (e.g., Spyder or VS Code)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flutter_todo_app.git
# Flutter Task Management App

A task management app built with Flutter that supports multiple languages, custom themes, and a structured directory layout for scalability and maintainability.

## Getting Started

To get the project dependencies and run the app on your device or emulator, use the following commands:

```bash
# Fetch project dependencies
flutter pub get

# Run the app
flutter run
```

## Folder Structure

The project follows a structured directory layout to ensure maintainability and scalability:

```bash
lib/
  ├── main.dart                # Entry point of the app
  ├── screens/                 # App screens (Home, AddTask, etc.)
  ├── widgets/                 # Custom widgets (TaskItem, CategoryWidget)
  ├── models/                  # Data models (Task, Category)
  ├── localization/            # Localization resources
  ├── theme/                   # Light and dark theme files
  └── utils/                   # Utility functions (e.g., date formatting)
```

## Localization

This app supports multiple languages. To add support for a new language, follow these steps:
```dart
arb-dir: lib/l10n
template-arb-file: app_en.arb
output-localization-file: app_localizations.dar
```

## Theming

The app supports both light and dark themes. You can customize the themes by editing the `light_theme.dart` and `dark_theme.dart` files located in the `lib/theme/` directory.

## Contributors

- **Abdelrahman Wael** - [GitHub Profile](https://github.com/AbdoJoker99)

