### Install Babel
```
npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/preset-react
```

### Install Webpack and loaders
```
npm install --save-dev webpack webpack-cli webpack-dev-server style-loader css-loader babel-loader
```

### Install React
```
npm install --save react react-dom
```

### Install React hot loader (optional)
```
npm install --save react-hot-loader
```

Note: You can safely install react-hot-loader as a regular dependency instead of a dev dependency as it automatically ensures it is not executed in production and the footprint is minimal.

[https://blog.usejournal.com/creating-a-react-app-from-scratch-f3c693b84658](https://blog.usejournal.com/creating-a-react-app-from-scratch-f3c693b84658)