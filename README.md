# npmdoc-dom-events

#### api documentation for  dom-events (v0.1.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-dom-events.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dom-events) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dom-events.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dom-events)

#### dom event binding and triggering

[![NPM](https://nodei.co/npm/dom-events.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dom-events)

- [https://npmdoc.github.io/node-npmdoc-dom-events/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dom-events/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dom-events/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dom-events/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dom-events/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dom-events/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "dom-events",
    "version": "0.1.1",
    "description": "dom event binding and triggering",
    "main": "index.js",
    "dependencies": {
        "synthetic-dom-events": "0.1.1"
    },
    "devDependencies": {
        "mocha": "1.8.1",
        "zuul": "0.0.7"
    },
    "scripts": {
        "test": "zuul --ui tdd test.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/shtylman/dom-events.git"
    },
    "keywords": [
        "event",
        "dom",
        "events"
    ],
    "author": "Roman Shtylman <shtylman@gmail.com>",
    "license": "MIT",
    "testling": {
        "files": "test.js",
        "browsers": [
            "ie/6..latest",
            "firefox/3.6..latest",
            "chrome/4.0..latest",
            "safari/5.1..latest"
        ],
        "harness": "mocha-tdd"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
