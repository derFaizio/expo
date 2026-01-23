# Overview
A sample React Native app with Expo

# Pre-requisites
1. Create an account on [Expo.dev](https://www.expo.dev)
2. Install the Expo Go app from the Google or Apple Store 

# Initial Setup
1. Initialize an expo app named `my-app`
`npx create-expo-app@latest`
1. Sign in to Expo dev and create a new Project
2. Select For an existing Codebase
3. Copy the EAS project with unique id
```
cd my-app
npx eas-cli@latest init --id <ProjectID>
```

# Getting started
1. Install dependencies

```
cd my-app
npm install
```

2. Login to expo
`npx expo login`

3. Start expo
`npx expo start`

4. If starting from Codespace
`npx expo start --tunnel`

# Run for different Platforms

1. Run Web
```
npm run web
```

2. Run iOS
```
npm run ios
```

3. Run Android
```
npm run web
```
