# Mobile App Submission — Palee Vang

## 1. Mobile Application Setup

The mobile application is located in the `mobile` folder. It uses React Native and Expo.

To run the application:

1. Open a terminal in the `mobile` directory.
2. Run `npm install` to install dependencies.
3. Run `npx expo start` to start the Expo development server.
4. Press `w` in the terminal to open the web version in a browser.

## 2. Mobile Application Interface

The application displays the Book Exchange welcome screen with options for Login, Register, and Book Exchange.

## 3. Code Changes

The `App.js` file was updated to include navigation-related imports and the `ActivityIndicator` import. Styles were also added for the bottom navigation bar, loading container, and error message.

## 4. Git Workflow

The following commands are used to track and submit the mobile notes.

### Check repository status

Command:

    git status

Example output:

    On branch main
    Changes not staged for commit:
      modified: mobile/App.js
      untracked: MobileStudent.MD

### Stage the mobile notes

Command:

    git add MobileStudent.MD

This stages only the mobile notes file, leaving `mobile/App.js` unstaged.

### Commit the mobile notes

Command:

    git commit -m "Add mobile submission notes"

This creates a commit containing the staged mobile notes.

### Push to GitHub

Command:

    git push origin main

This pushes the commit to my GitHub fork:

https://github.com/paleevang/IFT458-Middleware-2026