````markdown
# 🎱 Ask Me Anything - Flutter Magic 8 Ball App

A fun and interactive Magic 8 Ball app built with Flutter. Tap the ball to receive random, mysterious answers—just like a real magic 8 ball!

---

## 📱 Preview

![Magic 8 Ball Preview](images/screenshot1.png)  

---

## ✨ Features

- Clean and vibrant user interface
- Magic 8 Ball image changes on tap
- Displays one of five randomly chosen answers
- Responsive layout using `Expanded` and `TextButton`
- Smooth interaction and state management using `StatefulWidget`

---

## 🛠️ Technologies Used

- **Flutter** (UI Toolkit)
- **Dart** (Programming Language)
- **Material Design** (Widgets & structure)
- **Dart Random Class** (for random logic)
- **Asset Image Management**

---

## 📂 Project Structure

```bash
magic_8_ball_flutter/
├── images/
│   ├── ball0.png
│   ├── ball1.png
│   ├── ball2.png
│   ├── ball3.png
│   ├── ball4.png
│   ├── ball5.png
│   ├── screenshot1.png
│   └── screenshot2.png
├── lib/
│   └── main.dart
├── pubspec.yaml
└── README.md
````

---

## 🚀 Getting Started

### Prerequisites

* Flutter SDK (>=3.x recommended)
* Dart SDK
* Android Studio, VS Code, or any IDE with Flutter plugin

### Clone the Repository

```bash
git clone https://github.com/gtnt-sileshi/magic_8_ball_flutter.git
cd magic_8_ball_flutter
```

### Install Dependencies

```bash
flutter pub get
```

### Run the App

```bash
flutter run
```

---

## 📦 Dependencies

This app uses only the core Flutter packages—no third-party dependencies required.

```yaml
dependencies:
  flutter:
    sdk: flutter
```

---

## 🖼️ Assets

You’ll need 5 images named:

* `ball0.png`
* `ball1.png`
* `ball2.png`
* `ball3.png`
* `ball4.png`
* `ball5.png`
* `screenshot1.png`
* `screenshot2.png`

Place them inside the `images/` folder and reference them in `pubspec.yaml`:

```yaml
flutter:
  assets:
    - images/
```

---

## 🧠 How It Works

* The `MagicPage` widget is `Stateful` because the UI updates when you tap.
* Each time the user taps the image, `changeMagicAnswer()` is called.
* A random number between 1 and 5 is generated.
* The number changes the image file path: `images/ball$answer.png`.

---

## 📸 Screenshots

| Initial State              | After Tap                  |
| -------------------------- | -------------------------- |
| ![ball1](images/screenshot1.png) | ![ball3](images/screenshot2.png) |

---

## 📬 Contact

**Developer**: Getinet S. Zeleke
**Telegram**: [@gtnt\_slsh](https://t.me/gtnt_slsh)
**Email**: [gtntsileshi@gmail.com](mailto:gtntsileshi@gmail.com)

---

## 📝 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.

---

## 💡 Future Enhancements

* Add animated transitions between ball images
* Include text-based responses along with images
* Add sound effects or vibration
* Support dark mode toggle
* Make the answer set configurable

---

## 🙏 Acknowledgements

* [Flutter](https://flutter.dev/)
* [Dart Docs](https://dart.dev/)
* Inspired by the App Brewery's Flutter course

```

---
