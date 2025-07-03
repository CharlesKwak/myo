# Android Network Parser Sample

This repository contains a simple Android project that demonstrates communicating with a PHP backend and parsing XML results.

## Project Structure
- `parser/` – main Android application sources
- `android/` – **removed** (duplicate of `parser/`)
- `parser/bin/` and `parser/gen/` – generated build output (now removed from version control)

## Running the Example

### macOS
1. Install [Android Studio](https://developer.android.com/studio) and the required SDK tools.
2. Clone this repository and open the `parser` directory in Android Studio (`File` -> `Open`).
3. Allow Gradle to download dependencies and build the project. The removed `bin` and `gen` folders will be recreated automatically.
4. Connect an Android device or start an emulator, then press **Run** to launch the app.

### Linux
1. Install the latest Android Studio package (for example via Snap or direct download).
2. Clone this repository and open the `parser` directory.
3. Build and run the project as on macOS.

### Windows
1. Install Android Studio using the Windows installer.
2. Open the `parser` project and build/run it.

The application sends requests to the server URL defined in `MainActivity.java` (`SERVER_ADDRESS`). Ensure the backend is running or update the URL if needed.
