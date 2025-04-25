# Flutter Clock

A beautiful and customizable digital clock implementation built with Flutter. This project showcases a modern clock design with both dark and light themes, location-based functionality, and customizable display options.

## Features

- 🌓 Dark and Light theme support
- 🕒 12/24 hour time format
- 📍 Location-based display
- 🌡️ Temperature display with unit conversion
- 🎨 Beautiful animations and transitions
- 📱 Responsive design

## Screenshots

### Dark Theme
<img src='digital_clock/digital_dark.png' width='350'>

### Light Theme
<img src='digital_clock/digital_light.png' width='350'>

## Getting Started

### Prerequisites

- Flutter SDK
- Dart SDK
- An IDE (VS Code, Android Studio, or IntelliJ)

### Installation

1. Clone this repository
2. Navigate to the project directory
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## Customization

The clock supports various customization options through the `ClockModel` class:

- Toggle between 12/24 hour format
- Change location display
- Update temperature and units
- Switch between light and dark themes

## Project Structure

- `digital_clock/` - Main clock implementation
- `flutter_clock_helper/` - Helper utilities and models

## License

This project is licensed under the BSD License - see the LICENSE file for details.

## Acknowledgments

- Built with Flutter
- Uses the `intl` package for date formatting
- Implements vector math for animations
