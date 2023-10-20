# JatePWA19
~ Text Editor Web Application ~

## Description
This web application is a text editor that allows developers to create and manage notes or code snippets, with or without an internet connection. It uses IndexedDB for local storage and provides a user-friendly interface for creating, saving, and retrieving content.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Next-Gen JavaScript](#next-gen-javascript)
- [IndexedDB](#indexeddb)
- [Install as Desktop App](#install-as-desktop-app)
- [Service Worker](#service-worker)
- [Deployment to Heroku](#deployment-to-heroku)
- [Credits](#Credits)
- [License](#License)
- [Link](Link)

## Features
- Create and manage notes or code snippets.
- Works both online and offline.
- Backend server for serving the client.
- Bundles JavaScript files using webpack.
- Generates HTML, service worker, and manifest files.
- Supports next-generation JavaScript.
- Uses IndexedDB for content storage.
- Installable as a desktop app.
- Registered service worker using Workbox.

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/CodingObliqua/JatePWA19.git
2. **Navigate to the project directory:**

    ```bash
    cd JatePWA19
    ```

3. **Install the dependencies:**

    ```bash
    npm install
    ```

### Usage

1. **Start the application from the root directory:**

    ```bash
    npm run start
    ```

2. **Access the application in your web browser at [http://localhost:3000](http://localhost:3000).**

### Next-Gen JavaScript

This application uses next-generation JavaScript features to ensure modern and efficient code. It is designed to work smoothly in modern web browsers without errors.

### IndexedDB

IndexedDB is used for immediate database storage. Your content will be saved and retrieved seamlessly even if you close the text editor.

### Install as Desktop App

Click on the "Install" button to download the web application as an icon on your desktop. This allows you to use the text editor as a standalone desktop app.

### Service Worker

The application has a registered service worker using Workbox. It pre-caches static assets upon loading, ensuring a fast and reliable experience for users.

### Deployment to Heroku

To deploy this application to Heroku, make sure you have the proper build scripts for a webpack application in your project. Push your changes to your Heroku remote repository to initiate the deployment process.

```bash
git push heroku main
```

## Credits

No collaborators were involved in this project.

Third-party assets used:

- [Workbox](https://workboxjs.org/): A library for adding offline support to web apps.

## License

This project is licensed under the [MIT License](LICENSE).

## Link


This project is deployed on Heroku. You can access it [here](https://vast-lake-50168-e236f3d95a80.herokuapp.com/).

[GitHub Repository](https://github.com/CodingObliqua/JatePWA19)

![My Project Logo](/client/src/images/jatepic.JPG)