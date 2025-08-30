# Create Your First Mobile App

## Set Up the Project

Initialize Project

npx create-expo-app@latest .

The . indicates the project should be created in the current directory.

When prompted:

Do you want to move existing files to /app-example instead of deleting them? (Y/n):

Selected Y to preserve existing files.

Modify Home Screen

Opened the file:

app-example/app/(tabs)/index.tsx

Replaced the default text Welcome! with "First App Created".

Run and Test the Application

npx expo start

iOS Devices: Scan the QR code using the Camera app.

Android Devices: Scan the QR code using Expo Go.

Verified that the app displayed "First App Created".

## Reset the Project

npm run reset-project

The script asked whether to move existing files to /app-example; choosing Y preserved previous work.

Cleared caches, reinstalled dependencies, and reset the main folder to a clean Expo project.

### Observations

Resetting the project does not delete previous work when choosing Y.

Dependencies are reinstalled and caches cleared.

Useful to fix environment issues or return to a fresh template.

## Project Structure

prodev-mobile-app-0x00/
├── app/                     # New Expo app scaffold
├── assets/                  # Default assets
├── constants/               # Default constants
├── package.json             # Project metadata and dependencies
├── README.md                # Documentation
└── app-example/             # Previous files moved here after reset
    ├── app/
    │   └── (tabs)/          # Contains the modified home screen
    └── constants/           # Contains theme/color constants

## Repository Info

Repository: prodev-mobile-setup

Directory: prodev-mobile-app-0x00

Files Modified: README.md, app-example/app/(tabs)/index.tsx, app-example/constants/Colors.tsx

## Conclusion

The first mobile app was successfully created using Expo Router. The app runs on both Android and iOS devices using Expo Go, and the reset-project script preserves previous work while providing a clean environment for fresh development.

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

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

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

