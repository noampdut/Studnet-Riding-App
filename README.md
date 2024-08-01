# Student Riding Application


#### Overview
Welcome to the Student Riding Application! This innovative platform revolutionizes how students connect for rides. Designed to streamline the process of finding and sharing rides, this application leverages cutting-edge technology to provide a seamless and intelligent experience.

## Main Goal
Our primary goal is to facilitate efficient and convenient ride-sharing among students. By integrating advanced AI-driven matching algorithms and real-time notifications, we ensure a smooth and user-friendly experience for both drivers and passengers.

## Key Features
- **AI-Driven Matching**: Utilizes sophisticated AI algorithms to pair drivers and passengers effectively, ensuring optimal ride matches.
- **Recommendation System**: Provides personalized recommendations for potential ride matches based on user preferences and historical data.
- **Real-Time Notifications**: Keeps users informed with instant updates about ride statuses and new opportunities.
- **NLP-Enhanced Search**: Allows users to find rides and matches quickly and accurately with advanced search capabilities.
- **Google Maps Integration**: Provides seamless navigation and location services directly within the app for an enhanced user experience.
- **Third-Party API Connectivity**: Enhances functionality with integrations from external services.

## Links

- **Server-Side API**: [Student-Riding-Server](https://github.com/noampdut/Student-Riding-App-Server-Side-.git)
- **Android Client**: [Student-Riding-Android](https://github.com/noampdut/Student-Riding-App-Android.git)

## Setup and Running

### Server-Side Setup
1. Clone the server repository:
   ```bash
   git clone https://github.com/noampdut/Student-Riding-App-Server-Side-.git
   cd Student-Riding-Server
   ```
2. Configure MongoDB and update connection settings in `appsettings.json`.
3. Restore dependencies and run the server:
   ```bash
   dotnet restore
   dotnet run
   ```

### Android Client Setup
1. Clone the Android client repository:
   ```bash
   git clone https://github.com/noampdut/Student-Riding-App-Android.git
   cd Student-Riding-Android
   ```
2. Open the project in Android Studio.
3. Sync Gradle files.
4. Update the server URL in `SettingsActivity`.
5. Build and run the application on an emulator or physical device.

## Additional Notes
- Ensure the server is operational before running the Android client.
- The application has been praised for its innovative approach, including its AI-powered recommendation system, which has significantly enhanced user satisfaction.
