# npmdoc-blueimp-file-upload

#### api documentation for  [blueimp-file-upload (v9.18.0)](https://github.com/blueimp/jQuery-File-Upload)  [![npm package](https://img.shields.io/npm/v/npmdoc-blueimp-file-upload.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-blueimp-file-upload) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-blueimp-file-upload.svg)](https://travis-ci.org/npmdoc/node-npmdoc-blueimp-file-upload)

#### File Upload widget with multiple file selection, drag&drop support, progress bar, validation and preview images, audio and video for jQuery. Supports cross-domain, chunked and resumable file uploads. Works with any server-side platform (Google App Engine,

[![NPM](https://nodei.co/npm/blueimp-file-upload.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/blueimp-file-upload)

- [https://npmdoc.github.io/node-npmdoc-blueimp-file-upload/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-blueimp-file-upload/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-blueimp-file-upload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-blueimp-file-upload/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-blueimp-file-upload/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-blueimp-file-upload/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian Tschan",
        "url": "https://blueimp.net"
    },
    "bugs": {
        "url": "https://github.com/blueimp/jQuery-File-Upload/issues"
    },
    "dependencies": {
        "blueimp-canvas-to-blob": "3.5.0",
        "blueimp-load-image": "2.12.2",
        "blueimp-tmpl": "3.6.0"
    },
    "description": "File Upload widget with multiple file selection, drag&drop support, progress bar, validation and preview images, audio and video for jQuery. Supports cross-domain, chunked and resumable file uploads. Works with any server-side platform (Google App Engine,",
    "devDependencies": {
        "bower-json": "0.8.1",
        "jshint": "2.9.3"
    },
    "directories": {},
    "dist": {
        "shasum": "944281956740a15e4aca86e3b2088889af60809c",
        "tarball": "https://registry.npmjs.org/blueimp-file-upload/-/blueimp-file-upload-9.18.0.tgz"
    },
    "gitHead": "0b4af3c57b86b3c7147c4d7c75deb71a0133f0e3",
    "homepage": "https://github.com/blueimp/jQuery-File-Upload",
    "keywords": [
        "jquery",
        "file",
        "upload",
        "widget",
        "multiple",
        "selection",
        "drag",
        "drop",
        "progress",
        "preview",
        "cross-domain",
        "cross-site",
        "chunk",
        "resume",
        "gae",
        "go",
        "python",
        "php",
        "bootstrap"
    ],
    "license": "MIT",
    "main": "js/jquery.fileupload.js",
    "maintainers": [
        {
            "name": "blueimp"
        }
    ],
    "name": "blueimp-file-upload",
    "optionalDependencies": {
        "blueimp-canvas-to-blob": "3.5.0",
        "blueimp-load-image": "2.12.2",
        "blueimp-tmpl": "3.6.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/blueimp/jQuery-File-Upload.git"
    },
    "scripts": {
        "bower-version-update": "./bower-version-update.js",
        "lint": "jshint *.js js/*.js js/cors/*.js",
        "postversion": "git push --tags origin master && npm publish",
        "preversion": "npm test",
        "test": "npm run lint",
        "version": "npm run bower-version-update && git add bower.json"
    },
    "title": "jQuery File Upload",
    "version": "9.18.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
