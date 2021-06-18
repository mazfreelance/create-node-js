# Installation

## npm

### -- save : to install package and save it as a dependency in the package.json file
```shell
$ npm install npm-demo-testing-maz --save
```

## Test

### create anyfile on js for example index.js. replace code on below
```shell
var demo = require('npm-demo-testing-maz');
demo.printMsg();
```

### run command
```shell
$ node index.js
```

# Usage

# Tutorial to develop node module
```shell
$ npm init
```

## create index.js
```shell
exports.printMsg = function() {
console.log("This is a message from the demo package");
}
```

## push to git
```shell
$ git add.
$ git commit -m "Initial release"
$ git tag v0.0.1 
$ git push origin master --tags
```

## publish to npm package
### ** if not login or havent user yet
### npm register user
```shell
$ npm add user 
```
### npm login
```shell
$ npm login
```

### publish
```shell
$ npm publish
```
