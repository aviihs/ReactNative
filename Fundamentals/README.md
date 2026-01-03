# React Native – (Fundamentals):
  * React Native setup
  * Project structure
  * Running app
  * Components: View, Text, Image, ScrollView, TextInput, Button
  * Styling: Flexbox, StyleSheet, Inline style
  * Platform-specific code 
  * StatusBar customization

## Overview
Today was **Day 1** of learning **React Native fundamentals**.  
On this day, I learned how to set up React Native, understand the project structure, run the app on Android & iOS, use basic components, apply styling, handle platform-specific code, and customize the StatusBar

This README explains **what I learned**, **why it is used**, and **how it works** in a simple way.

## 1. React Native Setup

I use **Expo CLI** to set up a React Native project:

### Why Expo CLI?
- Beginner friendly
- Fast setup
- No need to install Android Studio or Xcode initially
- Good for learning and small to medium apps

**Command:**
```bash
npx create-expo-app `FolderName`
cd `FolderNAme`
npx expo start
```

## 2. Project structure

project-root/
│── app/
│── assets/
│── components/
│── constants/
│── hooks/
│── scripts/
│── node_modules/
│── app.json
│── package.json
│── tsconfig.json
│── .gitignore


###  app/
The **core of the application**.  
This folder uses **Expo Router’s file-based routing system**, meaning:
- Each file automatically becomes a screen or route
- Folder names represent navigation paths

Example:
app/index.tsx → Home Screen
app/profile.tsx → Profile Screen


### 🔹 assets/
Centralized storage for **static resources**, including:
- Images
- Custom fonts
- Brand icons

Keeping assets here helps maintain a clean and organized project.


### 🔹 components/
Contains **reusable UI components** such as:
- Custom Buttons
- Input fields
- Cards
- Headers

This follows the **DRY (Don't Repeat Yourself)** principle and improves code reusability.


### 🔹 constants/
Stores **global constants** used across the app:
- Theme colors
- API endpoints
- Layout spacing
- Font sizes

This ensures consistency and makes updates easier.


### 🔹 hooks/
Houses **custom React hooks** that manage logic outside UI components.

Examples:
- `useAuth` → Authentication logic
- `useTheme` → Theme management

This improves code readability and separation of concerns.


### 🔹 scripts/
Includes **automation and utility scripts** used for:
- Project maintenance
- Deployment tasks
- Build-related operations


### 🔹 node_modules/
Stores all **third-party libraries and dependencies** installed via npm or yarn.  
⚠️ This folder is auto-generated and should not be modified manually.


## ⚙️ Configuration Files

### 🔸 app.json
Expo configuration file that defines:
- App name
- App version
- Splash screen
- App icon
- Platform-specific settings


### 🔸 package.json
Tracks:
- Installed dependencies
- Development dependencies
- Project scripts (start, build, etc.)


### 🔸 tsconfig.json
Configures **TypeScript compiler options** to:
- Improve code quality
- Ensure type safety
- Reduce runtime errors


### 🔸 .gitignore
Specifies files and folders that Git should ignore, such as:
- `node_modules/`
- Build files
- Environment files

This keeps the repository clean and lightweight.



### TODAY WE LEARN ABOUT THE FOLDER AND FILE STRUCTURE OF REACT NATIVE AND HOW TO SET UP THE NATIVE APP FOR THE FIRST TIME SIMPLE AND IN AN EASY WAY. WILL CONTINUE OTHER TOMORROW.