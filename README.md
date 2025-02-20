# 🏡 Real Estate App

A **Flutter-based Real Estate** application following **Clean Architecture** principles with authentication, data caching, and localization. This project utilizes **streams** for real-time updates and **mock APIs** for development.
![Image](https://github.com/user-attachments/assets/5e0f74ff-625f-4c01-be44-7cb2fb06f477)
## ✨ Features
- **Clean Architecture** for maintainability and scalability
- **User Authentication** (Login & Signup)
- **Stream-based Data Handling** for real-time updates
- **Data Caching** for offline access
- **Localization** for multiple language support
- **Mock API Integration** for testing

## 🏗️ Tech Stack
- **Flutter** (UI & Business Logic)
- **Dart** (Programming Language)
- **Dio / Http** (API handling)
- ** SharedPreferences** (Local storage & caching)
- **Streams & RxDart** (Reactive programming)
- **  Intl** (Localization & Language support)

## 🔧 Project Structure (Clean Architecture)
```plaintext
lib/
│── core/             # Common utilities (constants, themes, helpers)
│── data/             # Data layer (Repositories, Models, API services)
│── domain/           # Business logic (Use cases, Entities)
│── presentation/     # UI layer (Screens, Widgets, State Management)
│── localization/     # Language files
└── main.dart         # App entry point
```

## 🚀 Setup & Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/real_estate_app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd real_estate_app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the app:
   ```sh
   flutter run
   ```

## 🌍 Localization
This app supports multiple languages. Modify `lib/localization/` to add new language support.

## 🛠 Future Enhancements
- Backend integration
- Push notifications
- Dark mode support

## 🤝 Contributing
Feel free to fork and contribute via pull requests! 🎉

## 📜 License
This project is licensed under the MIT License.
