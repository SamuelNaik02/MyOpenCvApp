# MyOpenCvApp

Cross-platform concept project combining an Android app (OpenCV + JNI) and a TypeScript web dashboard with Firebase integration.

---

## 1. Features Implemented (Android + Web)

### Android (Concept)

* Designed to capture live camera frames.
* Integrates OpenCV through JNI for real-time image processing.
* Performs color detection and shape recognition.
* Displays processed results within the app.

### Web (Concept)

* TypeScript-based dashboard for viewing processed image results.
* Real-time data updates planned via Firebase integration.
* Responsive layout with chart/graph placeholders for analysis.

---

## 2. Screenshots or GIF of the Working App

*(Prototype visuals shown below)*

![Android Demo](screenshots/android_demo.png)
![Web Dashboard](screenshots/web_dashboard.png)

---

## 3. Setup Instructions (NDK, OpenCV dependencies)

### Android (Planned)

1. Install Android Studio and NDK.
2. Download the OpenCV Android SDK and link it to the project.
3. Use JNI/C++ bridge for OpenCV functions.
4. Build and deploy on an Android device or emulator.

### Web

1. Install Node.js.
2. Run the following commands:

   ```bash
   cd web
   npm install
   npm run dev
   ```
3. Open the browser at `http://localhost:3000`.

---

## 4. Quick Explanation of Architecture (JNI, Frame Flow, TypeScript part)

### Architecture Overview

* **Camera (Java/Kotlin)** → captures frame.
* **JNI Bridge (C++)** → sends frame to native layer.
* **OpenCV** → processes image (detects colors/shapes).
* **Return to Android UI** → processed result shown on screen.
* **Web Dashboard (TypeScript)** → receives and displays processed data via Firebase or REST API.

```
Android Camera → JNI (C++) → OpenCV Processing → Firebase → Web Dashboard
```

---

## 5. Project Structure

```
MyOpenCvApp/
├── android-app/        # Android (OpenCV + JNI)
├── web/                # TypeScript frontend
├── screenshots/        # Placeholder images
└── README.md
```

---

## 6. Commit History Example

* `init: created project structure`
* `docs: added conceptual README`
* `chore: added placeholder screenshots`
* `docs: updated architecture section`

---

## 7. Future Enhancements

* Implement live OpenCV detection on Android.
* Connect with Firebase for data transfer.
* Build real web dashboard for visualization.

---

**Author:** Samuel Elumalai Naik
**GitHub:** [SamuelNaik02](https://github.com/SamuelNaik02)
