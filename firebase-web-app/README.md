# Firebase Web App

This project is a simple web application that detects whether the browser tab is focused or not. It provides real-time feedback to the user about the focus state of the tab.

## Project Structure

```
firebase-web-app
├── public
│   ├── index.html       # Main HTML file for the web application
│   └── README.md        # Documentation for the web application
├── firebase.json        # Firebase Hosting configuration
├── .firebaserc          # Firebase project configuration settings
└── README.md            # Overview and setup instructions for the project
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd firebase-web-app
   ```

2. **Install Firebase CLI** (if you haven't already):
   ```
   npm install -g firebase-tools
   ```

3. **Deploy the application**:
   Make sure you are logged into Firebase:
   ```
   firebase login
   ```
   Then deploy the application:
   ```
   firebase deploy
   ```

## Usage

Open the `public/index.html` file in a web browser. The application will display whether the tab is currently focused or if another application has focus.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements for the project.