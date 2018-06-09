# electron_hello_world

## enviroment for windows 10

### node.js 

1. download file

```
https://nodejs.org/ja/
software download click
```

2. install 

  * download file install

```
* notification
if it happen "Rolling back action" , you should select no install option node.js runtime. 
```

### electron

 * electron install

```
cd C:\Users\[username]
npm -g install electron-prebuilt

* if you miss install command on other directory, delete all node_modules
open bash on windows
rm -rf node_modules
```

### create project
* create free directory

### create project init
* create init package.json
```
npm init -y
```
* change package.json from init package.json to git update package.json
https://github.com/comsweetrollcakes/electron_hello_world/blob/master/package.json

### contents create
* create files

  * main.js  
https://github.com/comsweetrollcakes/electron_hello_world/blob/master/main.js

  * index.html  
https://github.com/comsweetrollcakes/electron_hello_world/blob/master/index.html

### execute electron
```
cd [project root directory]
electron electron_hello_world/
```
