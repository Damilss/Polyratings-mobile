 # PolyRatings Mobile (Expo)

Unofficial mobile client for Cal Poly’s PolyRatings (rate-my-professor style) dataset.

This repo contains an **Expo (React Native)** app targeting **iOS** and **Android**, built as a **read-only** experience (no accounts, no posting). The app consumes a **publicly reachable API** (preferred) rather than connecting directly to a database.

---

## Goals (v1)

- Browse professors
- Search + filter (name, department, course, etc.)
- Professor detail view (summary + ratings breakdown)
- Course list per professor (if available)
- Basic caching for fast, offline-friendly browsing
- Ship to **Apple App Store** and **Google Play Store**

---

## Tech Stack

- **Expo (React Native)**
- **TypeScript**
- Navigation: **Expo Router**
- Data fetching/cache: TBD
- Lint/format: ESLint 
---

# EXPO

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

- [Expo documentation](https://docs.expo.dev/)
