Steps Followed for Scaffolding

Navigate to the Project Directory
Opened the terminal and moved into the parent directory:

cd prodev-mobile-setup

Initialize a New Expo Project
Created a new Expo project using the latest Expo Router template:

npx create-expo-app@latest .

Modify the Home Screen

Opened the file app/(tabs)/index.tsx.

Located the default text Welcome!.

Changed it to:

** First App Created**

Run and Test the Application
Started the Expo development server:

npx expo start

iOS: Scanned the QR code with the Camera app.

Android: Scanned the QR code using the Expo Go app.

Reset the Application
Ran the reset command:

npm run reset-project

Observations from reset-project Command

The existing app content was moved into a folder named app-example.

The app now shows the default Expo screen on Expo Go, prompting:

"Edit app/index.tsx to edit this screen."

This means the reset cleared the customized code and reverted the project to a clean state.
