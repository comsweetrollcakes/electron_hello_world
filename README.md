# electron_hello_world

## Enviroment for windows 10

### Node.js

1. download file

``` download
https://nodejs.org/ja/
software download click
```

2. install  

* download file install

``` notification
* notification
if it happen "Rolling back action" , you should select no install option node.js runtime.
```

### Electron

* Electron install

``` install
cd C:\Users\[username]
npm -g install electron

* if you miss install command on other directory, delete all node_modules
open bash on windows
rm -rf node_modules
```

#### create project

* create free directory

#### create project init

* create init package.json

``` init
npm init -y
```

* init
 change package.json from init package.json to git update package.json  
`https://github.com/comsweetrollcakes/lectron_hello_world/blob/master/package.json`

### contents create

* create files

  * main.js  

  `https://github.com/comsweetrollcakes/electron_hello_world/blob/master/main.js`

  * index.html  

  `https://github.com/comsweetrollcakes/electron_hello_world/blob/master/index.html`

### execute Electron

``` execute
cd [project root directory]
electron electron_hello_world/
```

### package Electron

#### install package

``` package
npm install -g asar
npm i electron-packager -g
```

#### distribution

``` distribution
electron-packager ./electron_hello_world distribution --platform=win32 --arch=x64 --electronVersion=2.0.2 --overwrite --asar

* arch:all x32 x64 both
* platform: windows win32, mac darwin
```