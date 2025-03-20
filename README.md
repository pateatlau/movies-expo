# Movies App

## Introduction

Multi-platform movies app created using React Native Expo that runs on iOS, Android and Web.

## Prerequisites

Before you start, make sure you have the following installed:

- [Node.js](https://nodejs.org/en/download/) (version 16.13.0 or higher)
- [Git](https://git-scm.com/downloads)

## Getting Started

To start the project, run the following command:

```bash
npm install
```

This will install all the necessary dependencies for the project.

Next, run the following command to start the development server:

```bash
npm start
```

This will start the Expo runner and you can then select the platform you want to run the app on.

The development server will start at `http://localhost:8001`.

- Select a to run the app on Android
- Select i to run the app on iOS
- Select w to run the app on web

## References:

Publishing to Web:

1. eas login (1 time only)
2. eas init --id 0183765d-515a-4cd8-9728-1e969f485fcc (1 time only)
3. npx expo export --platform web
4. eas deploy --prod

Deploying to Android (DRAFT):

1. eas login
2. npx expo export --platform android
3. eas build --platform android
4. eas submit --platform android

Deploying to iOS (DRAFT):

1. eas login
2. npx expo export --platform ios
3. eas build --platform ios
4. eas submit --platform ios

Web deployment with EAS:

- https://docs.expo.dev/guides/publishing-websites/
- https://docs.expo.dev/eas/hosting/get-started/
- https://www.youtube.com/watch?v=NaKsfWciJLo
