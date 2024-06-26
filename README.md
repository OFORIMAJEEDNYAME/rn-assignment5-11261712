
### rn-assignment5-11261712s:

# React Native Banking App

This repository contains a React Native application for a banking app, featuring dynamic theming, navigation, and various screens for user interaction.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Screens](#screens)
  - [HomeScreen](#homescreen)
  - [SettingsScreen](#settingsscreen)
- [Theme Context](#theme-context)
- [Dependencies](#dependencies)
- [Setup Instructions](#setup-instructions)


## Introduction

This React Native application showcases a banking app UI with multiple screens and navigation. It leverages `react-navigation` for screen navigation and `react-native-elements` for UI components such as icons. The app supports dynamic theming using a `ThemeContext` provider, allowing users to switch between light and dark themes seamlessly.

## Features

- Dynamic theming (light and dark modes)
- Navigation between screens (Home and Settings)
- Profile header, action buttons, and transaction lists on HomeScreen
- Settings screen with options like language, profile settings, and theme toggle

## Screens

### HomeScreen

The `HomeScreen` displays a user profile header, a card image, action buttons for common banking tasks (e.g., send money, receive money), and a transaction list. The UI adapts to a dark theme based on user preference.

### SettingsScreen

The `SettingsScreen` provides options for configuring user settings such as language preferences, profile management, and password changes. It includes a switch for toggling between light and dark themes.

## Theme Context

The `ThemeContext` is utilized to manage the application-wide theme state. It provides the current theme mode (`isDarkTheme`) and a function (`toggleTheme`) to toggle between light and dark themes.

## Dependencies

The project relies on the following main dependencies:
- `@react-navigation/native`
- `react-navigation-stack`
- `react-native-elements`

These dependencies are essential for navigation management and UI component rendering within the application.

## Setup Instructions

To run this application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your/repository.git
   cd repository-name
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Ensure you have a suitable development environment set up for React Native (Xcode for iOS, Android Studio for Android).

4. Start the Metro Bundler:
   ```bash
   npx react-native start
   ```

5. Run the application on your preferred simulator or device:
   ```bash
   npx react-native run-ios
   # or
   npx react-native run-android
   ```
   ## Screenshots

![banking4](https://github.com/OFORIMAJEEDNYAME/rn-assignment5-11261712/assets/170121601/d4d03359-5f7b-4631-ba84-aa5a70af5a8e)
![banking3](https://github.com/OFORIMAJEEDNYAME/rn-assignment5-11261712/assets/170121601/e247d897-fb2d-4894-8927-d3cd2ae71a2b)
![banking2](https://github.com/OFORIMAJEEDNYAME/rn-assignment5-11261712/assets/170121601/ca1440a5-3209-4681-9436-ec55c74bc0af)
![banking1](https://github.com/OFORIMAJEEDNYAME/rn-assignment5-11261712/assets/170121601/e8e4eb5b-246a-426e-b20f-b8ac925f8be5)
   




