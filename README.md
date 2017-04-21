# npmdoc-phaser

#### api documentation for  [phaser (v2.6.2)](http://phaser.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-phaser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-phaser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-phaser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-phaser)

#### A fast, free and fun HTML5 Game Framework for Desktop and Mobile web browsers.

[![NPM](https://nodei.co/npm/phaser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phaser)

- [https://npmdoc.github.io/node-npmdoc-phaser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-phaser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phaser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phaser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-phaser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-phaser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "phaser",
    "version": "2.6.2",
    "release": "Kore Springs",
    "description": "A fast, free and fun HTML5 Game Framework for Desktop and Mobile web browsers.",
    "author": "Richard Davey <rdavey@gmail.com> (http://www.photonstorm.com)",
    "logo": "https://raw.github.com/photonstorm/phaser/master/phaser-logo-small.png",
    "homepage": "http://phaser.io",
    "bugs": "https://github.com/photonstorm/phaser/issues",
    "license": "MIT",
    "licenseUrl": "http://www.opensource.org/licenses/mit-license.php",
    "main": "./build/phaser.js",
    "repository": {
        "type": "git",
        "url": "https://photonstorm@github.com/photonstorm/phaser.git"
    },
    "scripts": {
        "test": "NODE_ENV=test grunt jshint"
    },
    "keywords": [
        "2d",
        "HTML5",
        "WebGL",
        "canvas",
        "game",
        "javascript",
        "physics",
        "tweens",
        "typescript",
        "web audio"
    ],
    "devDependencies": {
        "eslint": "^3.3.1",
        "grunt": "^0.4.5",
        "grunt-contrib-clean": "^0.5.0",
        "grunt-contrib-concat": "^0.4.0",
        "grunt-contrib-connect": "^0.7.1",
        "grunt-contrib-copy": "^0.5.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^0.4.0",
        "grunt-eslint": "^19.0.0",
        "grunt-git": "^0.3.3",
        "grunt-jsdoc": "~0.6.2-beta",
        "grunt-notify": "^0.3.0",
        "grunt-text-replace": "^0.3.11",
        "jsdoc": "^3.4.0",
        "load-grunt-config": "~0.7.2",
        "typescript": "1.4.1",
        "yuidocjs": "^0.3.50"
    },
    "typings": "./typescript/typings.json",
    "typescript": {
        "definitions": [
            "typescript/p2.d.ts",
            "typescript/phaser.comments.d.ts",
            "typescript/pixi.comments.d.ts"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
