# J.A.T.E - Just Another Text Editor (A Progressive Web Application)

## Description

JATE is a text editor that runs in your web browser. The project is a Progressive Web Application (PWA) that is designed to work even when the user is offline. It utilizes a number of data persistence techniques for storing and retrieving notes and code snippets.

One of the key aspects of JATE is its ability to use IndexedDB for storing data. The `idb` package, a lightweight wrapper around IndexedDB API used by tech giants like Google and Mozilla, powers this functionality. 

## Installation

You can clone the repository to your local machine for development purposes.

```
git clone <repository_link>
```

Once cloned, navigate into the project directory and install the necessary dependencies with:

```
npm install
```

To start the development server, you can run:

```
npm run server
```

For production, you can build the application with:

```
npm run build
```

The application can be deployed on Heroku using the instructions provided in this [Heroku Deployment Guide](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).

## Features

- **Offline Compatibility:** The application functions offline. Data is saved to IndexedDB, allowing you to access your notes and code snippets even without an internet connection.
- **Web App Installable:** The application meets the PWA criteria, meaning you can install it on your device like a native app.
- **Bundling:** Webpack is used to bundle JavaScript files, optimizing load and execution times.
- **Service Worker:** The application includes a service worker, enabling it to load quickly and work offline.

## Usage

Upon opening the application, you can start typing in the text editor. If you navigate away or close the window, your text will be saved automatically. When you return to the application, your text will be retrieved and displayed in the editor for you to continue where you left off.

## Deployment

The application can be deployed to Heroku. Remember to include the necessary start scripts in your package.json file.

## Contributing

This project is open for contributions. Developers can follow the standard Fork & Pull Request workflow to contribute to this project.

## License

This project is licensed under ISC.

## Contact

For any questions, feel free to reach out:

Github Profile: Oscar Zavala

Github username: rocas3096

Email: ozavala3096@gmail.com
