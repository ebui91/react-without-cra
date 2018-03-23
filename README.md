# react-without-cra
This project was NOT bootstrapped with Create-React-App.


## Description
Boilerplate setup with webpack and babel config for a React project.


## Dependencies
You'll need to install the following dependencies in order to use this project:
```
npm install --save-dev webpack
npm install --save-dev babel-loader
npm install --save-dev babel-core
npm install --save-dev babel-preset-es2015
npm install --save-dev babel-preset-react
npm install --save react
npm install --save react-dom
```

The dependencies are already included in the package.json file, so you can also run `npm install --save` in your CLI.


## Running the App
If you want to see your React app in action you can open up index.html directly, or if you prefer, create a simple HTTP server:

```
$ npm install http-server -D
$ ./node_modules/.bin/http-server dist -p 8080
```

Navigate to `http://localhost:8080` in the broswer to view your project.