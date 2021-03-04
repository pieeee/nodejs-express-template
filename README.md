Node.js Express Template
============
[![Current Version](https://img.shields.io/badge/version-1.0.0-green.svg)](https://github.com/IgorAntun/node-chat) ![Social](https://img.shields.io/discord/817046198547513425)

This is a node.js Express.js template for any backend node-express backend application.

## Setup
Clone this repo to your desktop and run npm install to install all the dependencies.

## NPM Scripts
```json
"build": "babel src --out-dir dist",
"test": "echo \"Error: no test specified\" && exit 1",
"dev": "nodemon --exec yarn restart",
"restart": "rimraf dist && yarn build && yarn start",
"start": "node dist/index.js"
```

## Features
- babel support
- eslint plugins
- prettier formatting

## Dependecies

|Packages          |Version  |
|------------------|---------|
|bcrypt            | 5.0.1   | 
|cookie-parser     | 1.4.5   |
|cors              | 2.8.5   |
|dotenv            | 8.2.0   |
|express           | 4.17.1  |
|jsonwebtoken      | 8.5.1   |
|mongoose          | 5.11.18 |
|morgan"           | 1.10.0  |

## Dev Dependencies
|Packages          |Version  |
|------------------|---------|
|@babel/cli|7.13.0
|@babel/core|7.13.8
|@babel/plugin-proposal-class-properties|7.13.0
|@babel/plugin-proposal-object-rest-spread|7.13.8
|@babel/preset-env|7.13.9
|babel-core|6.26.3
|babel-eslint|10.1.0
|cross-env|7.0.3
|eslint|7.21.0
|eslint-config-prettier|8.1.0
|eslint-config-standard|16.0.2
|eslint-friendly-formatter|4.0.1
|eslint-loader|4.0.2
|eslint-plugin-import|2.22.1
|eslint-plugin-node|11.1.0
|eslint-plugin-prettier|3.3.1
|eslint-plugin-promise|4.3.1
|eslint-plugin-standard|5.0.0
|nodemon|2.0.7
|prettier|2.2.1
|rimraf|3.0.2

## Repository Structure

📦nodejs-express-template
 ┣ 📂src
 ┃ ┗ 📜index.js
 ┣ 📜.babelrc
 ┣ 📜.eslintrc.js
 ┣ 📜.gitignore
 ┣ 📜.prettierrc.js
 ┣ 📜README.md
 ┣ 📜nodemon.json
 ┗ 📜package.json

## License
This project is licensed under the terms of the **MIT** license.