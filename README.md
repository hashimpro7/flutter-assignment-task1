# 📱 Flutter Internship Project – Login & Counter App with To-Do Screen

This project was developed as part of an internship task. It demonstrates a simple Flutter app with a login screen, a persistent counter using shared preferences, animated UI components, and navigation to a placeholder to-do screen.


## 🚀 Features

### 🔐 Login Page

* A simple UI for user login with text fields for email and password.
* Includes animation using the `animate_do` package for a dynamic appearance.
* On tapping the "Login" button, the user is navigated to the **Home Screen**.
* No backend authentication is implemented; it is a dummy login for UI demonstration.

### 🏠 Home Screen

* Displays a welcome message and animated UI elements.
* Implements a **counter** with `+` and `-` buttons.
* The counter value is saved using **`SharedPreferences`**, so it persists even after closing the app.
* A floating action button allows navigation to the **To-Do List Screen**.

### 🗒️ To-Do List Screen (Placeholder)

* A separate screen accessible from the Home Screen.
* Currently serves as a placeholder for future to-do list implementation.
* Demonstrates use of `Navigator` for screen transition.


## 🧭 Application Flow

1. **App Launch:**

   * The app launches with the `LoginPage` as the initial screen.

2. **Login Process:**

   * The user enters dummy email and password.
   * Upon pressing the login button, they are navigated to the `HomeScreen` using `Navigator.pushReplacement`.

3. **Home Screen Functionality:**

   * Background images are layered and animated for a dynamic UI.
   * A counter is displayed with increment (`+`) and decrement (`–`) buttons.
   * Counter value is stored and retrieved using `SharedPreferences`.
   * The floating button navigates to the `ToDoScreen`.

4. **To-Do Screen Navigation:**

   * A basic placeholder screen that simulates navigation and structure.
   * Prepares for future task management features.

## 📂 Project Structure

```bash
lib/
├── main.dart             # App entry point
├── login_page.dart       # Login UI with animations
├── home_screen.dart      # Counter functionality with SharedPreferences
└── todo_screen.dart      # To-Do list placeholder screen

assets/
└── images/
    ├── background.png
    └── background-2.png

## 🧰 Dependencies Used

| Package              | Purpose                                  |
| -------------------- | ---------------------------------------- |
| `flutter`            | Base SDK                                 |
| `shared_preferences` | Persistent storage for the counter value |
| `animate_do`         | Animated widgets and UI effects          |

Make sure to declare your assets in `pubspec.yaml`:

```yaml
flutter:
  assets:
    - assets/images/background.png
    - assets/images/background-2.png
```

---

💡 Concepts Practiced

* Stateless vs Stateful Widgets
* Persistent Storage using `SharedPreferences`
* UI animations using `animate_do`
* Navigation between screens with `Navigator`
* Responsive design using `MediaQuery`
* UI layering with `Stack` and `Positioned`
* Project structuring and asset management


## ✅ How to Run

1. **Clone the repository**:

   ```bash
   git clone [https://github.com/your-username/flutter-internship-task.git](https://github.com/hashimpro7/flutter-assignment-task1/tree/master)
   cd flutter-internship-task
   ```

2. **Install dependencies**:

   ```bash
  animate_do: ^3.1.2
  shared_preferences: ^2.5.3
  cupertino_icons: ^1.0.2

  run
  flutter pub get
   ```

3. **Run the app**:

   ```bash
   flutter run
   ```

## 🙋‍♂️ Author

This project was completed as part of an internship task by:

**Muhammad Hashim Shahid**
\[(https://github.com/hashimpro7)]
\[https://www.linkedin.com/in/hashim-shahid-5a620b26a]
