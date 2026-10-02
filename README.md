# repo-test-gpt

Small React Native project setup and run guide.

## Prerequisites

Install these before running the project:

- Node.js 18+
- npm or Yarn
- Git
- React Native CLI dependencies for your OS
- Android Studio for Android development
- Xcode for iOS development (macOS only)

## Create a new React Native app

```bash
npx @react-native-community/cli init MyReactNativeApp
cd MyReactNativeApp
```

## Install dependencies

```bash
npm install
```

Or with Yarn:

```bash
yarn install
```

## Run Metro

Start the React Native development server:

```bash
npm start
```

Or:

```bash
yarn start
```

## Run on Android

Make sure an Android emulator is running, or connect a physical device with USB debugging enabled.

```bash
npm run android
```

Or:

```bash
yarn android
```

## Run on iOS

Install CocoaPods dependencies first:

```bash
cd ios
pod install
cd ..
```

Then run:

```bash
npm run ios
```

Or:

```bash
yarn ios
```

## Common useful commands

```bash
# Run tests
npm test

# Check linting
npm run lint

# Reset Metro cache
npm start -- --reset-cache
```

## Troubleshooting

If the app does not start:

1. Confirm the emulator/device is connected.
2. Restart Metro with cache reset.
3. Reinstall dependencies with `npm install` or `yarn install`.
4. For iOS, run `cd ios && pod install && cd ..` again.

## Learn more

- React Native docs: https://reactnative.dev/docs/getting-started
