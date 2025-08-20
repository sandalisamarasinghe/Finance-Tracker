# ImiliPocket - Personal Finance Tracker

ImiliPocket is a modern Android application for tracking personal finances, designed specifically for students learning mobile development. The app provides a clean and intuitive interface for managing transactions, analyzing spending patterns, and maintaining a monthly budget.

## Features

### Core Features
1. Transaction Management
   - Add, edit, and delete transactions (income/expense)
   - Each transaction includes title, amount, category, and date
   - Local data storage using SharedPreferences

2. Category-wise Spending Analysis
   - Predefined categories (Food, Transport, Bills, etc.)
   - Visual representation with pie charts
   - Detailed breakdown of spending by category

3. Monthly Budget Setup
   - Set and track monthly budget
   - Visual progress indicator
   - Budget warnings

4. Data Persistence
   - Local storage using SharedPreferences
   - Backup and restore functionality

### Technical Details
- Built with Kotlin
- Modern Material Design UI
- Uses MPAndroidChart for visualizations
- Implements ViewBinding for view access
- Follows MVVM architecture pattern

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/imilipocket/
│   │   │   ├── models/
│   │   │   │   └── Transaction.kt
│   │   │   ├── ui/
│   │   │   │   ├── transactions/
│   │   │   │   ├── analysis/
│   │   │   │   └── settings/
│   │   │   └── utils/
│   │   │       └── DataManager.kt
│   │   └── res/
│   │       ├── layout/
│   │       ├── values/
│   │       └── drawable/
```

## Setup Instructions

1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle files
4. Run the app on an emulator or physical device

## Dependencies

- AndroidX Core KTX
- AndroidX AppCompat
- Material Design Components
- MPAndroidChart
- Gson for JSON handling

## Contributing

This project is designed for educational purposes. Feel free to fork and modify for learning purposes.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 