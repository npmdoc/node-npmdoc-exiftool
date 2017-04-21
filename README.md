# npmdoc-exiftool

#### api documentation for  exiftool (v0.0.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-exiftool.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-exiftool) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-exiftool.svg)](https://travis-ci.org/npmdoc/node-npmdoc-exiftool)

#### Metadata extraction from numerous filetypes including JPEG, PNG, PDF, MOV, WMV, MP3, MP4, and others.

[![NPM](https://nodei.co/npm/exiftool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/exiftool)

- [https://npmdoc.github.io/node-npmdoc-exiftool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-exiftool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-exiftool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-exiftool/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-exiftool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-exiftool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "exiftool",
    "version": "0.0.3",
    "description": "Metadata extraction from numerous filetypes including JPEG, PNG, PDF, MOV, WMV, MP3, MP4, and others.",
    "main": "./lib/exiftool",
    "author": {
        "name": "Nathan Peck"
    },
    "devDependencies": {
        "mocha": "1.17.1",
        "chai": "1.8.1"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/nathanpeck/exiftool.git"
    },
    "keywords": [
        "exif",
        "file",
        "metadata",
        "binary",
        "image",
        "video",
        "PNG",
        "PDF"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.githubusercontent.com/nathanpeck/exiftool/master/LICENSE"
        }
    ],
    "readmeFilename": "README.md",
    "scripts": {
        "test": "./node_modules/.bin/mocha -R spec -s 100 ./tests/test.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
