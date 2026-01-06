
# Wake-App Project

This repository contains two main folders: `mobile` and `web`, each with an independent project:

- **mobile**: Android mobile application (Android Studio, Kotlin)
- **web**: Web application (Angular)

Below you will find a description of the folder structure, as well as setup and run instructions for each project.

---

## Folder Structure

```
misw4302_ux/
│
├── mobile/         # Android mobile app (Kotlin, Android Studio)
│   └── wake_app/   # Main Android project
│
└── web/            # Web app (Angular)
    └── wake_app/   # Main Angular project
```

---

## Mobile App (`mobile/wake_app`)

This is a native Android application built with **Kotlin** and **Android Studio**. The project uses:

- **Programming Language:** Kotlin 1.9.0
- **Framework:** Android SDK (compileSdk 34, minSdk 27, targetSdk 34)
- **Build System:** Gradle 8.6.0
- **UI:** Android Jetpack (Navigation, ViewBinding, Material Components)

### How to Run the Mobile App

1. **Clone the repository:**
   ```bash
   git clone https://github.com/OrangeScript/misw4302_ux.git
   cd misw4302_ux
   ```
2. **Open in Android Studio:**
   - Open Android Studio
   - Select `Open an existing project` and choose `mobile/wake_app`
3. **Let Gradle sync and download dependencies.**
4. **Set up an Android emulator or connect a physical device.**
5. **Run the app:**
   - Click the green 'Run' button or use `Shift+F10`.
6. **Lazy Run:**
   - Visit the following [Link](https://www.figma.com/proto/Ew9s47fZBdySPtyGzMVIly/User-Expirience-Project?node-id=2-2441&t=wGix5spPQWINLYXS-1&starting-point-node-id=2%3A2441) To check the prototype


#### Project Overview
The app is a template Android project with a main activity and two fragments, using Jetpack Navigation for screen transitions. You can use this as a starting point for your own Android development.

---

## Web App (`web/wake_app`)

This is a web application built with **Angular 18** and **TypeScript**. The project uses:

- **Programming Language:** TypeScript
- **Framework:** Angular 18.2.x
- **Build System:** Angular CLI 18.2.4, Node.js

### How to Run the Web App

1. **Clone the repository:**
   ```bash
   git clone https://github.com/OrangeScript/misw4302_ux.git
   cd misw4302_ux
   ```
2. **Install Node.js** (if not already installed): [Download Node.js](https://nodejs.org/)
3. **Install Angular CLI:**
   ```bash
   npm install -g @angular/cli@18
   ```
4. **Install dependencies:**
   ```bash
   cd web/wake_app
   npm install
   ```
5. **Run the development server:**
   ```bash
   ng serve
   ```
   Open your browser at [http://localhost:4200](http://localhost:4200) to view the app.
6. **Lazy Run:**
   - Visit the following [Link](https://www.figma.com/proto/Ew9s47fZBdySPtyGzMVIly/User-Expirience-Project?node-id=89-3183&t=wGix5spPQWINLYXS-1&starting-point-node-id=89%3A3162) To check the prototype

#### Project Overview
The web app is a template Angular project generated with Angular CLI 18.2.4. It includes basic configuration and can be used as a starting point for building browser-based applications.

---

## Additional Notes

- Both projects are independent and can be developed or deployed separately.
- For more details, see the README files inside each project folder.

