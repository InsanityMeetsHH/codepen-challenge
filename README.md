# CodePen Challenge - InsanityMeetsHH

[**Demo page**](http://cpc.insanitymeetshh.net)

## Required
* [Node.js](http://nodejs.org/en/download/)
* [npm](http://www.npmjs.com/get-npm) `$ npm i npm@latest -g`
* [gulp-cli](https://www.npmjs.com/package/gulp-cli) `$ npm i gulp-cli@latest -g`
* PHP => 5.3

## Installation (Recommended)
```bash
$ git clone https://github.com/InsanityMeetsHH/codepen-challenge.git [project-name]
$ cd [project-name]
$ rm -rf .git
$ npm i
$ gulp build
```
Change `localServer` in [`gulpfile-config.json`](https://github.com/InsanityMeetsHH/gulp-templating/blob/master/gulpfile-config.dist.json) to your local server.

Possible local servers (examples): http://imhh-cpc.localhost/ or http://localhost/imhh-cpc/public/.

## Project Commands
|               | Description                                                                                                     |
|---------------|-----------------------------------------------------------------------------------------------------------------|
| gulp          | watch files and start [BrowserSync](https://www.npmjs.com/package/browser-sync)                                 |
| gulp build    | executes following tasks: cleanUp, scss, js, scssLint, jsLint, img, font, svg                                   |
| gulp cleanUp  | clean up public folder                                                                                          |
| gulp font     | copy font                                                                                                       |
| gulp img      | compress/copy img                                                                                               |
| gulp js       | uglify/minify/concat js                                                                                         |
| gulp jsLint   | checks js follows [lint rules](https://github.com/InsanityMeetsHH/gulp-templating/blob/master/js-lint.json)     |
| gulp scss     | compile/minify/concat scss                                                                                      |
| gulp scssLint | checks scss follows [lint rules](https://github.com/InsanityMeetsHH/gulp-templating/blob/master/scss-lint.json) |
| gulp svg      | compress/copy svg                                                                                               |
| gulp watch    | watch scss, js, img, font and svg files                                                                         |
