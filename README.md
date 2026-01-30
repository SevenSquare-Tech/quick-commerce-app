# Quick Commerce App (Flutter)

Project Name: quick-commerce-app
Version: 0.1.0

## Description

Quick Commerce App is a Flutter-based mobile application designed to support fast, on-demand commerce experiences.
The project is structured with clean asset management, modern Flutter packages, and secure storage practices.

This project is currently private and not published to pub.dev.

## SDK & Environment

- Flutter SDK: >= 3.0.5 < 4.0.0
- Dart SDK: Compatible with Flutter 3.x

## Dependencies

Core dependencies used in this project:

- flutter_dotenv (^5.1.0)  
  For managing environment variables securely.

- flutter_svg (^2.0.7)  
  To render SVG images in the app.

- fluttertoast (^8.2.2)  
  For lightweight toast notifications.

- share_plus (^7.0.2)  
  Enables sharing content from the app.

- lottie (^2.4.0)  
  Used for rich animations.

- flutter_cached_pdfview (^0.4.2)  
  Displays and caches PDF files.

- provider (^6.0.5)  
  State management solution.

- flutter_secure_storage (^8.0.0)  
  Secure storage for sensitive data.

- dio (^5.3.0)  
  Powerful HTTP client for API communication.

## Dev Dependencies

- flutter_test  
  For widget and unit testing.

- flutter_lints (^2.0.0)  
  Enforces best coding practices.

- flutter_native_splash  
  Generates native splash screens.

## Splash Screen Configuration

- Splash Image: Assets/splash2.png
- Background Color: #FFE141
- Platforms:
  - Android: Enabled
  - Android 12: Custom image and background color
  - iOS: Disabled
  - Web: Disabled

## Assets Structure

The following asset directories are configured:

- Assets/
- Assets/cimgs/
- Assets/Categories/
- Assets/SubCategories/
- Assets/Products/
- Assets/Images/

## Fonts

Custom font family used: Catamaran

Included font weights:

- Thin (100)
- Light (300)
- Regular (400)
- Medium (500)
- SemiBold (600)
- Bold (700)
- ExtraBold (800)

## How to Run

1. Install Flutter SDK (3.x)
2. Run `flutter pub get`
3. Connect a device or emulator
4. Run `flutter run`

## Notes

- Ensure asset paths are case-sensitive.
- Environment variables should be placed in a `.env` file.
- Secure values should be stored using flutter_secure_storage.
