# npmdoc-suitcss

#### api documentation for  suitcss (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-suitcss.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-suitcss) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-suitcss.svg)](https://travis-ci.org/npmdoc/node-npmdoc-suitcss)

#### CSS base styles, utilities, and structural components for web apps

[![NPM](https://nodei.co/npm/suitcss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/suitcss)

- [https://npmdoc.github.io/node-npmdoc-suitcss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-suitcss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-suitcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-suitcss/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-suitcss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-suitcss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "suitcss",
    "version": "2.0.0",
    "description": "CSS base styles, utilities, and structural components for web apps",
    "style": "index.css",
    "files": [
        "index.css"
    ],
    "dependencies": {
        "suitcss-base": "^2.0.0",
        "suitcss-components": "^1.0.1",
        "suitcss-utils": "^1.0.0"
    },
    "devDependencies": {
        "suitcss-preprocessor": "^2.0.0"
    },
    "scripts": {
        "build": "npm run setup && npm run preprocess",
        "preprocess": "suitcss index.css build/build.css",
        "setup": "npm install"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/suitcss/suit.git"
    },
    "keywords": [
        "browser",
        "css-components",
        "css-utilities",
        "suitcss",
        "style"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
