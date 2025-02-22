# Ignite Vision App

## Overview

Ignite Vision is a comprehensive mobile application designed for efficient travel and expense management, document scanning, and vehicle tracking. It offers both online and offline functionality, dynamic configuration, and robust security features.

GitHub Repository: [git@github.com:charlpcronje/Ignite-Vision-App.git](https://github.com/charlpcronje/Ignite-Vision-App)

## Features

- **Document Scanning**: High-quality document scanning with OCR capabilities.
- **Expense Management**: Log and track expenses with automatic categorization.
- **Trip Tracking**: GPS-based trip logging with support for multi-segment trips.
- **Vehicle Management**: Track vehicle usage, maintenance, and associated expenses.
- **Offline Mode**: Full functionality even without an internet connection.
- **Dynamic Configuration**: Flexible app settings manageable through JSON files.
- **Secure Data Handling**: End-to-end encryption for sensitive data.
- **Project-Based Logging**: All activities can be associated with specific projects.

## For Users

### Getting Started

1. Download the app from the App Store (iOS) or Google Play Store (Android).
2. Sign up for an account or log in with your provided credentials.
3. Grant necessary permissions for full app functionality (camera, location, etc.).
4. Set up your profile and preferences in the app settings.

### Key Functionalities

- **Scanning Documents**: Use the camera icon to scan receipts, ID cards, or vehicle documents.
- **Logging Expenses**: Tap the '+' icon in the Expenses tab to add new expenses.
- **Recording Trips**: Start a new trip from the Trips tab. The app will automatically track your route.
- **Managing Vehicles**: Add and manage vehicles in the Vehicles section.
- **Offline Usage**: The app works offline. Data will sync when you're back online.
- **Project Selection**: Always ensure you've selected the correct project before logging activities.

### Support

For support, please contact our helpdesk at support@ignitevision.com or use the in-app help feature.

## For Developers

### Tech Stack

- **Frontend**: Flutter for cross-platform mobile development
- **Backend**: [Specify backend technology, e.g., Node.js, Django]
- **Database**: SQLite (local), [Specify cloud database, e.g., PostgreSQL] (server)
- **APIs**: RESTful API with dynamic endpoints
- **Authentication**: Token-based authentication with refresh mechanism

### Setting Up the Development Environment

1. Clone the repository:
   ```
   git clone git@github.com:charlpcronje/Ignite-Vision-App.git
   ```
2. Install Flutter and Dart SDK.
3. Install dependencies:
   ```
   flutter pub get
   ```
4. Set up your IDE (VS Code or Android Studio recommended) with Flutter and Dart plugins.

### Project Structure

- `lib/`: Main application code
  - `models/`: Data models
  - `screens/`: UI screens
  - `services/`: Business logic and API interactions
  - `widgets/`: Reusable UI components
- `assets/`: Static assets (images, fonts)
- `test/`: Unit and widget tests

### Key Components

- `DatabaseService`: Manages local SQLite database
- `SyncService`: Handles data synchronization between local and server
- `ApiService`: Manages API communications
- `AuthService`: Handles user authentication
- `EncryptionService`: Manages data encryption and decryption

### Dynamic Configuration

The app uses JSON configuration files for flexible settings management. These files are fetched from a remote server and can be updated without app redeployment.

### Testing

Run tests using:
```
flutter test
```

Ensure comprehensive unit tests for all services and widget tests for UI components.

### Contribution Guidelines

1. Fork the repository and create your branch from `main`.
2. Write clear, commented, and testable code.
3. Ensure all tests pass and add new tests for new features.
4. Create a pull request with a comprehensive description of changes.

## For Stakeholders

### Project Goals

Ignite Vision aims to streamline travel and expense management processes, improving efficiency and accuracy in business operations.

### Key Benefits

- **Cost Reduction**: Automated expense tracking and reporting.
- **Improved Compliance**: Ensures adherence to company policies and regulations.
- **Enhanced Productivity**: Simplifies trip planning and expense management.
- **Data-Driven Insights**: Provides valuable data for business decision-making.

### Roadmap

- **Q3 2024**: Launch of core features (document scanning, expense logging, trip tracking)
- **Q4 2024**: Implementation of advanced analytics and reporting
- **Q1 2025**: Integration with popular accounting software
- **Q2 2025**: Launch of web dashboard for administrators

### Feedback and Continuous Improvement

We value your feedback. Please send your suggestions and reports to charl@webally.co.za

---

© 2024 Ignite. All rights reserved.