# EXAMPLE STRUCTURE PROJECT

This is dummy for structure folder flutter

## Getting Started

This project is a starting point for a Flutter application.

flutter_project/
├── android/                # Native Android code and settings
├── ios/                    # Native iOS code and settings
├── lib/                    # Main directory for Dart and Flutter code
│   ├── main.dart           # Entry point of the app
│   ├── core/               # Core functionalities used across the app
│   │   ├── constants/      # App-wide constants like colors, strings, dimensions
│   │   │   ├── colors.dart
│   │   │   ├── strings.dart
│   │   │   ├── dimensions.dart
│   │   ├── utils/          # Utility classes and helpers
│   │   │   ├── validators.dart
│   │   │   ├── extensions.dart
│   │   ├── services/       # App-wide services (e.g., API calls, local storage)
│   │   │   ├── api_service.dart
│   │   │   ├── local_storage_service.dart
│   │   ├── models/         # Data models
│   │       ├── user_model.dart
│   │       ├── product_model.dart
│   ├── features/           # Organized by app features or modules
│   │   ├── auth/           # Authentication-related features
│   │   │   ├── screens/    # UI for authentication
│   │   │   │   ├── login_screen.dart
│   │   │   │   ├── signup_screen.dart
│   │   │   ├── widgets/    # Reusable components for auth
│   │   │   │   ├── auth_button.dart
│   │   │   ├── providers/  # State management (e.g., Riverpod, Provider)
│   │       │   ├── auth_provider.dart
│   │   ├── home/           # Home screen features
│   │       ├── screens/
│   │       │   ├── home_screen.dart
│   │       │   ├── details_screen.dart
│   │       ├── widgets/
│   │       │   ├── product_card.dart
│   │       ├── providers/
│   │           ├── home_provider.dart
│   ├── common/             # Common shared widgets or components
│   │   ├── app_bar.dart
│   │   ├── button.dart
│   │   ├── input_field.dart
│   ├── config/             # Configuration settings
│   │   ├── env.dart        # Environment configurations
│   │   ├── routes.dart     # App navigation routes
│   │   ├── themes.dart     # Theme configuration
├── test/                   # Unit and widget tests
│   ├── main_test.dart
│   ├── features/           # Tests organized by features
│       ├── auth_test.dart
│       ├── home_test.dart
├── assets/                 # Static assets like images, fonts
│   ├── images/
│   │   ├── logo.png
│   │   ├── background.jpg
│   ├── fonts/
│       ├── Roboto-Regular.ttf
│       ├── Roboto-Bold.ttf
├── pubspec.yaml            # Flutter configuration file
├── README.md               # Project documentation
