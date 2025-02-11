# Aqar Live Coding - Problem Statement

## Problem Statement

- Given the sample data in `/mock` folder, build a simple app to display the data in a list
- The app should have a home screen that displays a list of listings
- When the listing is clicked, open a detail screen showing all the images within a selected listing
- The app should be running on Android Emulator

### Home Screen Requirements

Design Reference:

![Home Screen](https://share.cleanshot.com/Q9zR518D+)

- Display a list of listings (properties)
- Each listing (property) should display the:
  - English category name as title, based on listing.category value. For example `101 = Apartment For Booking`
  - First listing image as thumbnail
  - Properly formatted price (without currency)
  - Area size in square meters
  - Address

### Detail Screen Requirements

Design Reference:

![Detail Screen](https://share.cleanshot.com/w5TqBhxn+)

- Show list of images in proper resolution
- User should be able to go back to home screen

### Extra Points

- Implement a button to favorite / unfavorite a listing and persist this value on app restart

## What are allowed during this session

- Search on Google, any other search engine to help you learn and apply what you need
- Use 3rd party npm library
- Use AI coding assistant within the IDE as autocomplete assistant
- Ask the interviewer for clarification

## What are not allowed during this session

- Copy and pasting code from StackOverflow or any other website
- Using AI code generator like Lovable, Bolt, etc to create the test app
- Modify the mock data

========== ========== ==========

## Welcome to your Expo app 👋

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
