# Central Mindanao Newswatch

Central Mindanao Newswatch is a feature-rich Android application designed to keep users informed about local news in Central Mindanao, world headlines, and real-time weather updates. Built with a modern Android stack, it leverages Firebase for real-time data synchronization and cloud services.

## 🚀 Features

-   **Live News Feed:** Real-time updates on local newspapers and documents stored in Firebase Firestore.
-   **World Headlines:** Integration with external News APIs to provide global news coverage.
-   **Weather Integration:** Current weather conditions and 5-day forecasts for Malaybalay City and surrounding areas using OpenWeatherMap API.
-   **Push Notifications:** Instant alerts for new newspaper uploads and private messages using Firebase Cloud Messaging (FCM).
-   **Personalized Experience:**
    -   **Bookmark System:** Save important articles for offline reference.
    -   **Search & Filter:** Easily find news by title or category.
    -   **User Profiles:** Custom profile images and real-time online status.
-   **Communication:** In-app messaging features for user interaction.
-   **Modern UI/UX:**
    -   Material Design 3 components.
    -   Dark/Light theme support via `ThemeHelper`.
    -   Accessibility filters.
    -   Smooth animations with Lottie.

## 🛠 Tech Stack

-   **Language:** Java / Kotlin
-   **Architecture:** Follows modern Android development practices.
-   **Backend:** 
    -   Firebase Authentication (Email/Google Sign-In)
    -   Firebase Firestore (NoSQL database)
    -   Firebase Storage (Image/Document hosting)
    -   Firebase Cloud Messaging (Notifications)
-   **Networking:** Retrofit 2 & Gson for API consumption.
-   **Image Loading:** Glide for efficient image caching and display.
-   **UI Components:** Material Components, SwipeRefreshLayout, RecyclerView, DrawerLayout.

## 📦 Dependencies

Major dependencies used in the project:

-   `androidx.appcompat:appcompat`
-   `com.google.android.material:material`
-   `com.google.firebase:firebase-bom` (Auth, Firestore, Storage, Messaging)
-   `com.squareup.retrofit2:retrofit`
-   `com.github.bumptech.glide:glide`
-   `com.airbnb.android:lottie`

## ⚙️ Setup & Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/CentralMindanaoNewswatch.git
    ```
2.  **Firebase Configuration:**
    -   Create a new project in the [Firebase Console](https://console.firebase.google.com/).
    -   Add an Android app to your Firebase project with the package name `com.example.centralmindanaonewswatch`.
    -   Download the `google-services.json` file and place it in the `app/` directory.
    -   Enable Authentication, Firestore, and Storage in the Firebase Console.
3.  **API Keys:**
    -   The application uses OpenWeatherMap and NewsAPI. Ensure valid API keys are configured in the source code (e.g., in `UserActivity.java` or a secure `local.properties`).
4.  **Build:**
    -   Open the project in Android Studio.
    -   Sync Project with Gradle Files.
    -   Run the application on an emulator or physical device.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
