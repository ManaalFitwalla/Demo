# Technology Stack

## Build System

- **Build Tool**: Gradle (Kotlin DSL)
- **Android Gradle Plugin**: 9.2.1
- **Java Version**: 11

## Dependencies (via libs.versions.toml)

### Core Libraries
- **AndroidX Core KTX**: 1.19.0
- **AppCompat**: 1.7.1
- **ConstraintLayout**: 2.2.1
- **Material Components**: 1.14.0
- **Activity KTX**: 1.13.0

### Testing Libraries
- **JUnit**: 4.13.2
- **AndroidX JUnit**: 1.3.0
- **Espresso Core**: 3.7.0

## Common Commands

| Command | Purpose |
|---------|---------|
| `./gradlew build` | Build the project |
| `./gradlew test` | Run unit tests |
| `./gradlew connectedAndroidTest` | Run instrumentation tests |
| `./gradlew assembleDebug` | Build debug APK |
| `./gradlew assembleRelease` | Build release APK |

## IDE

- **Android Studio**: Standard Android development environment
- **Language**: Kotlin (primary), Java (if needed)

## Key Configuration

- **Namespace**: com.example.demo
- **Application ID**: com.example.demo
- **Min SDK**: 29
- **Target SDK**: 36