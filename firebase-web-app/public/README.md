# Firebase Web App

This web application is designed to detect whether the browser tab is focused or not. It provides a simple user interface that updates the status based on the focus state of the tab.

## Purpose

The main purpose of this application is to demonstrate how to detect focus changes in a web browser. This can be useful for applications that need to respond to user engagement or inactivity.

## How to Use

1. Clone the repository to your local machine.
2. Navigate to the `firebase-web-app` directory.
3. Open the `public/index.html` file in a web browser.
4. Observe the status message that indicates whether the tab is currently focused or not.

## Deployment

To deploy this application using Firebase Hosting, follow these steps:

1. Ensure you have the Firebase CLI installed. If not, install it using npm:
   ```
   npm install -g firebase-tools
   ```
2. Authenticate with your Firebase account:
   ```
   firebase login
   ```
3. Initialize your Firebase project (if not already done):
   ```
   firebase init
   ```
4. Deploy the application:
   ```
   firebase deploy
   ```

After deployment, your application will be live and accessible via the provided Firebase Hosting URL.