# Mobile Development Setup & First Expo App

## 0. Setting Up and Testing Your Mobile Development Environment

### Objective

Mobile development requires more resources than web development, so we’re using the **Expo Framework** with **React Native**. Expo Go allows us to test our apps directly on a physical device without relying on costly emulators or hardware.

### Tools Installed

- **Node.js LTS** (latest recommended version)
- **Visual Studio Code (VS Code)**
- **Operating System**: (macOS/Linux/Windows)
- **Expo Go** installed on physical device (Android/iOS)

### Why Expo Go?

Expo Go makes it easy to run and test React Native apps on real devices. It avoids the complexity of managing emulators for multiple platforms and versions, and works seamlessly with both iOS and Android.

### Setup Process

1. Installed **Expo Go**:

   - Android → from Google Play Store
   - iOS → from Apple App Store
   - Official link: [expo.dev/go](https://expo.dev/go)

2. Opened **Expo Go** and created an account (or logged into existing account).

3. Connected phone and computer to the **same Wi-Fi network**.

4. Verified that Expo Go was ready to run apps by scanning QR codes from the development server.

### Challenges Faced

- Needed to ensure phone and laptop were on the same Wi-Fi network.
- First-time bundle loading took longer but worked smoothly afterwards.

---

## 1. Create Your First Mobile App

### Objective

Set up and scaffold the first React Native mobile app using the **Expo Router template**, understand the structure, and run it on a real device.

### Steps

#### 1. Navigate to Project Directory

```bash
cd prodev-mobile-setup

```

#### 2. Create Project

Initialized new Expo project with Expo Router template:

```bash
npx create-expo-app@latest .
```

#### 3. Modify the Home Screen

Opened: app/(tabs)/index.tsx

Found default text: Welcome!

Changed it to:

** First App Created**

#### 4. Run and Test Application

Started development server:

```bash
npx expo start
```

iOS: scanned QR code with Camera app.

Android: scanned QR code with Expo Go app.

App loaded successfully on phone.

#### 5. Reset Project

Ran reset command:

```bash
npm run reset-project
```

Observations After Reset

Reset cleared cached data, dependencies, and configurations.

App returned to its freshly initialized state (like a clean install).

Helpful for resolving issues and ensuring a consistent environment.

Summary

Environment setup completed with Node.js, VS Code, and Expo Go.

Successfully created and modified a new Expo project.

Verified the app running on a physical device.

Learned how resetting works and how it affects the project state.
