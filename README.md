# Movie App

A Flutter app to browse, search, and manage movies with Firebase authentication and Cloud Firestore backend.  
Built with Riverpod for state management and featuring a sleek Cupertino-inspired UI.

---

## Features

- **User Authentication:**
  - Phone number login with OTP verification via Firebase Auth
  - Google Sign-In support
  - Email/password login (if implemented)
- **Movie Browsing:**
  - Multiple categories (New Releases, Popular, Top Rated, and genres like Action, Comedy, Horror, Sci-Fi, etc.)
  - Grid view of movies with cached images for smooth performance
- **Movie Details:**
  - Detailed screen for each movie showing synopsis, ratings, and more
- **Search:**
  - Search movies by title from a dedicated search screen
- **Theme Management:**
  - Toggle between light and dark themes by tapping the app title
- **State Management:**
  - Riverpod to handle app state efficiently
- **User Feedback:**
  - Loading animations while fetching data
  - Toast notifications for errors or important actions
- **URL Launcher:**
  - Open external links such as trailers or official pages

---

## Screenshots

*Add screenshots here to showcase your app UI*

---

## Getting Started

### Prerequisites

- Flutter SDK ([flutter.dev](https://flutter.dev/docs/get-started/install))
- Firebase project setup ([console.firebase.google.com](https://console.firebase.google.com))

### Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/yourusername/movie_app.git
    cd movie_app
    ```

2. Get dependencies:
    ```bash
    flutter pub get
    ```

3. Configure Firebase:
   - Follow the [Firebase Flutter Setup](https://firebase.flutter.dev/docs/overview)
   - Add `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) files to the respective folders

4. Run the app:
    ```bash
    flutter run
    ```

---

## Folder Structure

- `lib/`
  - `screens/` — UI screens like HomeScreen, LoginScreen, PhoneLoginScreen, MovieDetailScreen
  - `models/` — Movie data models
  - `providers/` — Riverpod providers managing state
  - `theme_provider.dart` — Theme management logic

---

## Dependencies

- `cupertino_icons`
- `firebase_core`
- `firebase_auth`
- `google_sign_in`
- `cloud_firestore`
- `flutter_riverpod`
- `fluttertoast`
- `loading_animation_widget`
- `cached_network_image`
- `url_launcher`

---

## License

MIT © [Vikas Salvi]

---

## Contact

Feel free to reach out at [vikassalvi693@gmail.com] 

