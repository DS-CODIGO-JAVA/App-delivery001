# App Delivery

An Android application for food delivery, built with Java and XML layouts in Android Studio.

## Overview

App Delivery is an academic mobile project developed as part of my Systems Development course at ETEC Uirapuru. It was created to practice native Android development, user interface design with XML and the structure of a Gradle-based Android project.

## Goals

- Practice native Android development with Java
- Design screens and layouts using XML
- Organize an Android project built with Gradle (Kotlin DSL)
- Explore the Android Studio development workflow, including the emulator and device testing

## Tech Stack

| Layer      | Technology                |
|------------|---------------------------|
| Language   | Java                      |
| Interface  | XML layouts               |
| Build tool | Gradle (Kotlin DSL)       |
| IDE        | Android Studio            |
| Platform   | Android                   |

## Project Structure

```
App-delivery001/
├── app/                    Android application module (source code and resources)
├── gradle/                 Gradle wrapper configuration
├── build.gradle.kts        Project-level build configuration
├── settings.gradle.kts     Project settings and modules
├── gradle.properties       Gradle properties
└── README.md
```

## Getting Started

### Prerequisites

- Android Studio (latest stable version)
- Android SDK installed through Android Studio
- An Android emulator or a physical device with USB debugging enabled

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/DS-CODIGO-JAVA/App-delivery001.git
   ```

2. Open the project folder in Android Studio.

3. Wait for the Gradle sync to finish. Android Studio downloads the required dependencies automatically.

4. Select an emulator or a connected device and click **Run**.

## Screenshots

Add screenshots of the application here:

```
![Home screen](docs/home.png)
![Order screen](docs/order.png)
```

## Roadmap

- Add a backend or local database for orders
- Improve the interface with Material Design components
- Add navigation between all screens
- Add unit and UI tests

## Author

**Fabricio**
GitHub: [@DevFcodes](https://github.com/DevFcodes)
Systems Development student at ETEC Uirapuru
