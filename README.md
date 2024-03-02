<a name="top"></a>
# JATE - A Progressive Web Applications (PWA): Text Editor ![Static Badge](https://img.shields.io/badge/License-MIT-blue?style=plastic)

## Table of Contents

- [Overview](#overview)
- [User Story](#user-story)
- [Features](#features)
- [Screenshot](#screenshot)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [GitHub](#github)
- [License](#license)

## Overview

This is a progressive web application (PWA) that serves as a text editor. It allows users to create and edit notes or code snippets both online and offline. The application features data persistence using IndexedDB, ensuring that user content is saved locally and can be retrieved reliably. Additionally, it is bundled with webpack, utilizes service workers with workbox for caching, and can be installed as a PWA.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Features

```md
1. IndexedDB Integration: The application utilizes IndexedDB to create an object store for storing user-generated content, ensuring data persistence even when offline.

2. Offline Functionality: Users can access and use the text editor even without an internet connection, thanks to the IndexedDB storage mechanism.

3. Auto-Saving: The application automatically saves content entered into the text editor whenever the DOM window is unfocused, ensuring that users' work is continuously preserved.

4. Webpack Bundling: The JavaScript files of the application are bundled using webpack, ensuring optimized performance and efficient loading.

5. Service Worker with Workbox: A service worker is implemented using Workbox, enabling caching of static assets and providing offline support for the application.

6. JavaScript Support: The application utilizes modern JavaScript features, such as async/await, ensuring compatibility with the latest browser standards.

7. Manifest.json Generation: A manifest.json file is generated using the WebpackPwaManifest plugin, facilitating the installation of the PWA and defining its appearance and behavior.

8. Installable as PWA: Users can install the text editor as a Progressive Web Application, allowing them to access it directly from their device's home screen and enjoy a native-like experience.
```

## Screenshot

![Comparison of the browser app and the downloaded app.](./Assets/browser-app-side-by-side.jpg)

## Usage

Simply click on the link here to access the web app: [JATE](https://wk-19-pwa-texteditor-1.onrender.com)

## Technologies Used

![Static Badge](https://img.shields.io/badge/IndexedDB-green?style=plastic)

![Static Badge](https://img.shields.io/badge/Babel-maroon?style=plastic)

![Static Badge](https://img.shields.io/badge/Service_Worker_with_Workbox-orange?style=plastic)

![Static Badge](https://img.shields.io/badge/Webpack-purple?style=plastic)

![Static Badge](https://img.shields.io/badge/WebpackPwaManifest-navy?style=plastic)

## GitHub
[Visit my GitHub Profile here!](https://github.com/CYCBrian)

## License
The project is covered under the following license:
[MIT](https://choosealicense.com/licenses/mit)

- - -
[Back to Top](#top)
- - -
© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
