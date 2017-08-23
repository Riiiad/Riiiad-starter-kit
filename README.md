# Riiiad Starter Kit

A light package for compiling Sass, Pug and running a dev server
This package is inspired by the Traversy Media and Dev Tips.
Check out they starter kits they are awesome.

### Version
1.0.0

## Usage

If you don't want to use pug in your projects just delete the gulp-pug line from the package.json file and comment out the pug part in the gulpfile.js.
Or you can also use the Starter Pack from Bard Traversy.

### Installation

Install the dependencies (gulp, gulp-sass, gulp-pug, gulp-concat, gulp-imagemin, gulp-uglify, del, browser-sync)

```sh
$ npm install
```

### Run

This will watch your sass/pug files, compile them and run your dev server at http://localhost:3000

```sh
$ npm start
```

### Deploy

Run this command to create the dist folder and your files will be ready to deploy. Just upload the files in the dist to your server.

```sh
$ gulp deploy
```
### Help

Run this commman to see the all commands.

```sh
$ gulp help
```
