# React tutorial
## Install Nodejs
Nodejs is open-source server enviroment that uses JavaScript on the server.
For installation run command:
```
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```

## Install NPM (update)
Npm is a package manager tool for Node.js:
```
sudo npm install npm@latest -g
```

## Install Create-react-app tool
With `npm` we should install `create-react-app` tool. We will use that to create
a new project in React.
```
$ npm install create-react-app
```

First thing first, we need to install a module provided by Facebook. It helps
us to create simple react apps:
After installation run following command:
```
$ npm create-react-app <project-name>
```
## Running the application
After the successful creation of our project, we can run that locally:
```
cd <project-name>
npm start
```
The react application starts on port `3000` and opens a new tab in our browser.
(`http://localhost:3000`)

# Install React-MDL
## Material Design Lite
Install Material components for the web locally:
```
$ npm i material-components-web
```
Then install all Node dependencies:
```
$ npm install --save-dev webpack webpack-cli webpack-dev-server css-loader \
sass-loader sass extract-loader file-loader
```

# First steps
## Remove unnecessaries files
favicon.ico + manifest.json + logo.svg

## src/App.js
1. remove line with `import logo ...`
2. Than clean all the code inside the `return`


