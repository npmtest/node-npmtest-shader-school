# npmtest-shader-school

#### basic test coverage for  [shader-school (v1.1.1)](http://nodeschool.io/#shader-school)  [![npm package](https://img.shields.io/npm/v/npmtest-shader-school.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shader-school) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shader-school.svg)](https://travis-ci.org/npmtest/node-npmtest-shader-school)

#### Self directed GLSL lessons

[![NPM](https://nodei.co/npm/shader-school.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shader-school)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shader-school/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shader-school/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shader-school/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shader-school/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shader-school/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-shader-school/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-shader-school/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shader-school/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shader-school/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shader-school/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shader-school/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shader-school/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shader-school/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shader-school/build/test-report.html](https://npmtest.github.io/node-npmtest-shader-school/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shader-school/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shader-school/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shader-school/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shader-school/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shader-school/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shader-school/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shader-school/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shader-school/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Hugh Kennedy <hughskennedy@gmail.com> (http://hughsk.io/)",
        "Mikola Lysenko <mikolalysenko@gmail.com> (http://0fps.net)",
        "Chris Dickinson <chris@neversaw.us> (http://neversaw.us)"
    ],
    "bin": {
        "shader-school": "index.js"
    },
    "bugs": {
        "url": "https://github.com/stackgl/shader-school/issues"
    },
    "dependencies": {
        "a-big-triangle": "0.0.0",
        "apprise": "^1.0.0",
        "autoprefixer": "^1.2.0",
        "baboon-image": "^1.0.0",
        "beefy": "^2.0.2",
        "brfs": "^1.1.1",
        "browser-menu": "^0.1.0",
        "browserify": "^6.3.2",
        "canvas-fit": "0.0.0",
        "chalk": "^0.4.0",
        "clamp": "^1.0.0",
        "conway-hart": "^0.1.0",
        "domify": "^1.2.2",
        "ecstatic": "^1.0.1",
        "envify": "^1.2.1",
        "findup-element": "0.0.0",
        "frame-debounce": "0.0.0",
        "gl-axes": "^2.2.3",
        "gl-buffer": "^2.0.8",
        "gl-compare": "^1.0.0",
        "gl-compare-sidebar": "^1.1.1",
        "gl-context": "^0.1.0",
        "gl-fbo": "^1.1.2",
        "gl-fbo-matching": "^1.0.0",
        "gl-matrix": "^2.1.0",
        "gl-texture2d": "^1.2.0",
        "gl-vao": "^1.1.3",
        "glsldoc": "0.0.4",
        "glslify": "^1.5.0",
        "glslify-live": "^2.0.3",
        "google-fonts": "0.0.0",
        "highlight.js": "^8.0.0",
        "inquirer": "^0.5.1",
        "insert-css": "^0.1.1",
        "marked": "^0.3.2",
        "mesh-normals": "^1.0.0",
        "mkdirp": "^0.5.0",
        "mouse-position": "^1.0.0",
        "mouse-pressed": "0.0.1",
        "ndarray": "^1.0.15",
        "ndarray-distance": "0.0.0",
        "opener": "^1.3.0",
        "quotemeta": "0.0.0",
        "raf": "^2.0.1",
        "remove-element": "0.0.0",
        "rework": "^0.20.3",
        "rework-inline": "^0.2.0",
        "rework-npm": "^0.6.1",
        "right-now": "^1.0.0",
        "sidenote": "^1.0.0",
        "sliced": "0.0.5",
        "stanford-dragon": "^1.0.0",
        "wordwrap": "0.0.2",
        "xhr": "^1.9.0",
        "zfill": "0.0.2"
    },
    "description": "Self directed GLSL lessons",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "007fd9d522ea6daaa55b452adf6e129157ae83c7",
        "tarball": "https://registry.npmjs.org/shader-school/-/shader-school-1.1.1.tgz"
    },
    "gitHead": "e82c666e5b0df4bbf5039078da04cc8205e37a81",
    "homepage": "http://nodeschool.io/#shader-school",
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "chrisdickinson"
        },
        {
            "name": "hughsk"
        },
        {
            "name": "mattdesl"
        },
        {
            "name": "mikkoh"
        },
        {
            "name": "mikolalysenko"
        },
        {
            "name": "rezaali"
        },
        {
            "name": "substack"
        },
        {
            "name": "tatumcreative"
        },
        {
            "name": "thibauts"
        },
        {
            "name": "wwwtyro"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "shader-school",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stackgl/shader-school.git"
    },
    "scripts": {
        "pack": "rm -rf answers; rm -rf node_modules && npm install && npm dedupe && node prepack && find . -type file | grep -v workshop.tar.gz | grep -v .git | tar -cvzf ./workshop.tar.gz -T - && node postpack",
        "start": "node start.js",
        "test": "echo \"Error: no test specified\" && exit 1",
        "postinstall": "npm rebuild --prefix ./"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
