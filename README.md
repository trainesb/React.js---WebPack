# React.js-Webpack-Babel
How to create an app with React.js, Babel and Webpack

```C
npm init -y
npm i -S react react-dom
```

Add ```react-native``` if we are building a mobile app.

## Babel
Babel is used to convert ES5 & ES6 code, so that it's backwards compatibale with older browsers.

### Packages
1. ***babel-core:*** The main engine of babel
2. ***babel-preset-env:*** Support for ES5 and ES6
3. ***babel-preset-react:*** Support to use babel with react
4. ***babel-loader:*** The communication link between Webpack and Babel
```C
npm i -D babel-core babel-loader babel-preset-env babel-preset-react
```

## Webpack
### Packages
1. ***webpack:*** The main engine
2. ***webpack-cli:*** Adds the ability to access some webpack commands like starting the dev server, creating a development/production build, etc...
3. ***webpack-dev-server:*** Server for development
4. ***html-webpack-plugin:*** Adds the abiltiy to create HTML templates
```C
npm i -D webpack webpack-cli webpack-dev-server html-webpack-plugin
```
