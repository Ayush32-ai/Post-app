# Post-app
# Reddit-like Flutter App

This Flutter app fetches and displays posts from an API in a style similar to Reddit. Users can view posts with options to upvote and downvote.

## Project Setup Instructions

1. **Install Flutter**: Ensure you have Flutter installed on your machine. Follow the installation guide on the [official Flutter website](https://flutter.dev/docs/get-started/install).
2. **Set Up an Editor**: Use a code editor like Visual Studio Code or Android Studio. Install the Flutter and Dart plugins for your chosen editor.
3. **Create a New Flutter Project**: Run `flutter create reddit_like_app` in your terminal, then navigate into the project directory with `cd reddit_like_app`.
4. **Replace the Default Code**: Open the `lib/main.dart` file and replace its contents with the provided code.
5. **Add Dependencies**: Open the `pubspec.yaml` file and ensure the `http` package is included under dependencies:
   ```yaml
   dependencies:
     flutter:
       sdk: flutter
       http: ^1.3.0 # or the latest version
