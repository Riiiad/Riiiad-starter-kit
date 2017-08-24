# Riiiad Starter Kit

A starter package for compiling Sass, Pug and running a dev server.


This package is inspired by the Traversy Media and Dev Tips starter kits.
Check out they starter kits they are awesome.


TM: https://github.com/bradtraversy/sass_starter_pack
DevTips: https://github.com/DevTips/DevTips-Starter-Kit

### Version

1.0.5


### Installation

Install the dependencies (gulp, gulp-sass, gulp-pug, gulp-concat, gulp-imagemin, gulp-uglify, del, browser-sync)

```sh
$ npm install
```

(Optional)Install gulp globally if you want to run the gulp command in your CLI.

```sh
$ npm install -g gulp
```

## Usage

This kit works with pug by default. You change the pug files in the pug folder and the files are compiled to html.

In the assets folder you upload the images and js files this folder will be copy to the build folder.

Never change the src/index.html or the assets/css/ files because it will be overwritten with the compiled files.

### Run

This will watch your sass/pug files and run your dev server at http://localhost:3000

```sh
$ npm start
```

### Run without Pug(testing)

There is a `gulp no-pug` option, this will only run sass compiling and the dev server. You just change the index.html file in the src/no-pug folder.

You have to refresh the site to see changes, auto-refresh is still not working.

```sh
$ gulp no-pug
```

### Ready for deployment

After you are ready to deploy you project. Run this command to create the dist folder and your files will be ready to deploy. Just upload the files in the dist to your server.

```sh
$ gulp build
```
### Help

Run this command to see the all available commands.

```sh
$ gulp help
```
