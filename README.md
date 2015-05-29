# Homey Development Kit

Create Homey apps with ease! If you're only looking to get the Development Kit, download a pre-built version from [https://developers.athom.nl]().

This repository is meant for development of the Development Kit itself.

![](https://developers.athom.nl/img/devkit.png)

### Run instructions

Requirements: [nw.js](http://nwjs.io/), [node.js with npm](https://nodejs.org/), [grunt](http://gruntjs.com/), [bower](http://bower.io/)

1. clone this repo: ```git clone https://github.com/athombv/devkit.git```
2. cd to the directory: ```cd devkit```
3. install the node packages: ```npm install```
4. install the bower packages: ```bower install```
5. make a symbolic link (or copy) [devkit-core](https://github.com/printhom/devkit-core) so there's a folder `core` next to `package.json`, `app.js` etc.
6. Run `grunt`
7. Download a pre-built nw.js binary from http://nwjs.io
  1. OS X: execute `nw .`
   2. Windows: drag the devkit folder on the `nw.exe` binary

### Docs
Please read them at [devkit-core](https://github.com/printhom/devkit-core).
