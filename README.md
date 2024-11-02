# Todo App with React Native

## Dependencies

- **React Native** - ReactJS-based framework that can use native platform capabilities
- **Expo** - Toolset for building and delivering React Native apps
- **React Navigation(v6)** - Routing and navigation
- **NativeBase(v3)** - Themable component library
- **React Native Reanimated** - Animations
- **Moti** - Helper module for Reanimated 2
- **React Native SVG** - Drawing SVG

## Project Structure

$PROJECT_ROOT
|-- App.tsx         # Entry point
|-- src             
    |-- screens     # Screen components
    |-- components  # UI components
    |-- utils       # Custom hooks and helpers
    |-- assets      # Image files

## Useful Commands

Create a new app:

```
npx create-expo-app todo-app-rn -t expo-template-blank-typescript
```

Run the app on iOS:

```
npx expo start --ios
```

Add prettier:

```
npm install -D prettier
```

For navigation, screens etc.:

```
npm install @react-navigation/native @react-navigation/drawer react-native-screens
npm install native-base react-native-svg styled-components styled-system
npm install moti react-native-reanimated
npm install react-native-safe-area-context shortid @types/shortid expo-linking
```
