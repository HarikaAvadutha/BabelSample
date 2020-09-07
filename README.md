Run the below command to create package.json file

> npm init

Run the below command to install npm packages required for Babel:

> npm install babel-cli babel-preset-env

Create a .babelrc file to determine the version of the source javascript

Configure package.json to run babel
In the package.json file, there is a property named scripts, add below line to that

> "build": "babel src -d folder"

Above command will convert the ES6 code from src directory and outputs the ES5 code in the dist folder.

Create a src folder and add a main.js file with ES6 concepts

Run below command

> npm run build
