# Nitzan Learning React Native 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Learning topics

### Part 1 - Expo tutorial
* [x] Create an app
   * Create new app with `create-expo-app`.
   * The basic structure of expo app.
   * The main screen (index.tsx).
   * Basic components - `View` and `Text`.
* [x] Add navigation
   * Expo router in the app directory.
   * Layouts files.
   * Defining different screens with `Stack` component.
   * Navigate between screens with `Link` component.
   * Not found route - `+not-found.tsx`.
   * Grouped some screen together with parentheses `()`, and creating `Tabs` buttons.
* [x] Build a screen
   * Using `expo-image` library.
   * Divide components into seperate files - the components directory.
   * Create button with `Pressable` component.
* [x] Use an image picker
   * Using the library expo-image-picker to pick an image from the gallery of the local device, and edit the image before uploading it to the app.
   * Using an async function `launchImageLibraryAsync()` from this library.
   * Understanding the result that this function return, and how to use the `uri`, and the status of the `canceled` property. 
   * Implement all in the app.
* [x] Create a modal
   * Use `<Modal>` component.
   * Using with the `@expo/vector-icons` library. 
   * Creating list of emojies for the modal from the assets directory.
   * Using `ImageSourcePropType` from react-native for put the emoji on the image.
* [x] Add gestures
   * Learn how to manipulate an image with duble tap.
   * Learn how to manipulate an image with drag it and change the location on the screen.
* [ ] Take a screenshot
* [ ] Handle platform differecnes
* [ ] Configure status bar, splash screen and app icon
* [ ] Learning resources
 
### Part 2 - EAS tutorial
* [ ] Configuration development build
* [ ] Android development build
* [ ] iOS development build for simulators
* [ ] iOS development build for devices
* [ ] Multiple app variants
* [ ] Internal distribution build
* [ ] Manage app versions
* [ ] Android build production
* [ ] iOS production build
* [ ] Share previews
* [ ] Builds from GitHub

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
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)

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
