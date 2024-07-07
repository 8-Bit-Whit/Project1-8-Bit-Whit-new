# Colorado STEM Ecosystem Android App

![App Screenshot][img.png](img.png)

## What this app does

The Colorado STEM Ecosystem Android App is designed to connect and inform stakeholders in the STEM education community across Colorado. It offers the following key features:

1. Information about the Colorado STEM Ecosystem
2. A network visualization of ecosystem partners
3. Resources for STEM education
4. Ability to join or contact the ecosystem
5. Information on the ecosystem's mission and how to donate

The app aims to facilitate collaboration, share resources, and promote STEM education initiatives throughout Colorado.

## Overview

This Android application serves as a mobile platform for the Colorado STEM Ecosystem, providing information, resources, and networking opportunities for STEM education stakeholders in Colorado.

## Features

- **Home Screen**: Introduces users to the app and provides navigation to other sections.
- **About Ecosystem**: Detailed information about the Colorado STEM Ecosystem.
- **Join**: Allows users to join the ecosystem or request more information.
- **Network**: Displays a visualization of the ecosystem's network and stakeholders.
- **Mission**: Outlines the mission and goals of the Colorado STEM Ecosystem.
- **Donate**: Provides information on how to support the ecosystem.
- **Contact**: Contact information and form for reaching out to the organization.
- **Resources**: Links to various STEM education resources and partner organizations.

## Technical Implementation

- Developed for Android using Kotlin
- Implements Jetpack Navigation for seamless navigation between fragments
- Uses a NavigationDrawer for main menu navigation
- Includes tablet-specific layouts for better use of screen real estate on larger devices
- Implements message passing between fragments and activities for data transfer

## Key Components

- Multiple Activities: MainActivity, LoginActivity, WelcomeActivity
- 8+ Fragments: HomeFragment, AboutEcoFragment, JoinFragment, NetworkFragment, MissionFragment, DonateFragment, ContactFragment, ResourcesFragment
- Advanced Navigation: Drawer navigation with Jetpack Navigation
- Tablet Support: Includes sw600dp layouts for tablet optimization

## Setup and Installation
## How to run the app

1. Clone the repository
2. Open the project in Android Studio
3. Wait for Gradle to sync and download necessary dependencies
4. Connect an android device or emulator
3. click the 'Run' button in Android Studio to build and run the app on your device

Note: Ensure you have the latest version of Android Studio and the Android SDK installed.

## Requirements

- Android Studio 4.0+
- Android SDK 21+
- Kotlin 1.5+

Note: Ensure you have the latest version of Android Studio and the Android SDK installed.

## How to use the app

1. Upon launching, you'll see the home screen with an overview of the ecosystem
2. Use the navigation drawer (accessible by swiping from the left edge or tapping the menu icon) to access different sections of the app
3. Explore each section for specific information:
- About: Learn about the Colorado STEM Ecosystem
- Join: Fill out a membership form, linked to web, to join the ecosystem
- Network: View a visualization of the ecosystem's partners
- Mission: Read about the ecosystem's goals and objectives
- Donate: Find information on how to support the ecosystem
- Contact: Get in touch with the ecosystem organizers
- Resources: Access STEM education resources and partner links
4. Use the back button or home icon or navigation drawer to navigate between screens

## Third-party sources used

1. Android Jetpack Libraries (androidx.*): For modern Android development practices
2. Material Design Components: For consistent and modern UI elements
3. [Kumu](https://kumu.io/): Used for creating and embedding the network visualization
4. [Google Forms](https://www.google.com/forms/about/): Used for the 'Join' form functionality

## Additional Information

- The app is designed to work on both phones and tablets, with a specific layout for larger screens (tablets)
- Internet connection is required for some features like the network visualization and accessing external resources
- The app uses Jetpack Navigation for handling navigation between different sections
- Data is passed between different parts of the app using Android's built-in message passing mechanisms

For developers looking to contribute or modify the app, please refer to the inline code comments for more detailed information about each component's functionality.
## Contributing

Contributions to improve the app are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - whaddad@msudenver.edu

Project Link: [https://github.com/yourusername/repo_name](https://github.com/yourusername/repo_name)