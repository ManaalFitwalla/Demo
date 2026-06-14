# Project Structure

```
Demo/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/demo/     # Kotlin source code
│   │   │   │   └── MainActivity.kt         # Main activity
│   │   │   ├── res/                        # Resources
│   │   │   │   ├── drawable/               # Image resources
│   │   │   │   ├── layout/                 # UI layouts
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── mipmap-*/               # App launcher icons (dpi variants)
│   │   │   │   ├── values/                 # String/color/theme resources
│   │   │   │   ├── values-night/           # Dark theme resources
│   │   │   │   └── xml/                    # XML configs (backup, data extraction)
│   │   │   └── AndroidManifest.xml
│   │   ├── test/                           # Unit tests
│   │   │   └── java/com/example/demo/
│   │   └── androidTest/                    # Instrumentation tests
│   │       └── java/com/example/demo/
│   ├── build.gradle.kts                    # App-level Gradle config
│   └── proguard-rules.pro                  # ProGuard rules
├── gradle/
│   ├── wrapper/                            # Gradle wrapper
│   └── libs.versions.toml                  # Dependency versions
├── build.gradle.kts                        # Root Gradle config
├── settings.gradle.kts                     # Project settings
├── gradle.properties                       # Gradle properties
├── gradlew / gradlew.bat                   # Gradle wrapper scripts
└── local.properties                        # Local config (ignored by git)
```

## Key Directories

- **app/src/main/java**: Main application code, organized by package
- **app/src/main/res**: All application resources
- **app/src/test**: Unit tests (JUnit)
- **app/src/androidTest**: Instrumentation tests (Espresso/JUnit)

## Package Naming

All source files follow the pattern: `com.example.demo`