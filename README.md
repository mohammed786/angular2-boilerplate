# angular2-boilerplate

## Run the following commmands in cmd

* npm install @angular/common @angular/compiler @angular/core @angular/forms @angular/http @angular/platform-browser @angular/platform-browser-dynamic @angular/router --save
* npm install core-js rxjs zone.js --save
* npm install typescript --save-dev
* npm install typings --save-dev
* npm install webpack webpack-dev-server --save-dev
* npm install angular2-template-loader awesome-typescript-loader css-loader file-loader html-loader null-loader raw-loader style-loader to-string-loader --save-dev
* npm install html-webpack-plugin webpack-merge extract-text-webpack-plugin --save-dev
* npm install rimraf --save-dev
* node_modules\.bin\typings install
* Replace script option in **package.json** with below:
```javascript
"scripts": {
    "start": "webpack-dev-server --inline --progress --port 8080",
    "postinstall": "typings install"
},
```
