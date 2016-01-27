# Indian Energy Projects Map

MapBox.js map and datatable showing Indian Energy project information.

This project uses gulp.js for task automation.

## Requirements

* git - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
* node - https://nodejs.org/en/download/
* gulp - https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md


## Development

Work in the ```src/``` folder. You can manually transpile your ES6 syntax back to ES5 using ```gulp babel```. The ```gulp watch``` task monitors changes in the src folder and runs the build task.


## Install

```bash
$ git clone https://github.com/NREL/eere-ie-projects-map.git
$ npm install
```

## Build

```bash
$ gulp build
```

## Deploy

```bash
$ gulp deploy
```
