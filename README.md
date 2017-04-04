# api documentation for  [how-to-npm (v2.4.2)](https://github.com/workshopper/how-to-npm#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-how-to-npm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-how-to-npm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-how-to-npm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-how-to-npm)
#### A module to teach you how to module.

[![NPM](https://nodei.co/npm/how-to-npm.png?downloads=true)](https://www.npmjs.com/package/how-to-npm)

[![apidoc](https://npmdoc.github.io/node-npmdoc-how-to-npm/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-how-to-npm_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-how-to-npm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-how-to-npm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-how-to-npm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "email": "i@izs.me",
        "url": "http://blog.izs.me/"
    },
    "bin": {
        "how-to-npm": "index.js"
    },
    "bugs": {
        "url": "https://github.com/workshopper/how-to-npm/issues"
    },
    "bundleDependencies": [
        "workshopper-adventure",
        "concat-stream",
        "mkdirp",
        "rimraf",
        "semver",
        "which"
    ],
    "dependencies": {
        "concat-stream": "^1.4.7",
        "mkdirp": "^0.5.0",
        "rimraf": "^2.2.8",
        "semver": "^4.2.0",
        "update-notifier": "^1.0.3",
        "which": "^1.0.8",
        "workshopper-adventure": "^5.0.3"
    },
    "description": "A module to teach you how to module.",
    "devDependencies": {
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "b4b58942294079a48d260e11000d0bf629e4db0b",
        "tarball": "https://registry.npmjs.org/how-to-npm/-/how-to-npm-2.4.2.tgz"
    },
    "gitHead": "58d88f3b31ec07869dd1372fbc68833e1610ee95",
    "homepage": "https://github.com/workshopper/how-to-npm#readme",
    "keywords": [
        "workshop",
        "adventure",
        "tutorial",
        "tutor",
        "npm"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "isaacs",
            "email": "i@izs.me"
        },
        {
            "name": "julianduque",
            "email": "julianduquej@gmail.com"
        },
        {
            "name": "tdd",
            "email": "tdd@tddsworld.com"
        },
        {
            "name": "watilde",
            "email": "daijiro.wachi@gmail.com"
        }
    ],
    "name": "how-to-npm",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/workshopper/how-to-npm.git"
    },
    "scripts": {
        "test": "standard"
    },
    "version": "2.4.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module how-to-npm](#apidoc.module.how-to-npm)
1.  [function <span class="apidocSignatureSpan">how-to-npm.</span>__ ()](#apidoc.element.how-to-npm.__)
1.  [function <span class="apidocSignatureSpan">how-to-npm.</span>__n ()](#apidoc.element.how-to-npm.__n)
1.  [function <span class="apidocSignatureSpan">how-to-npm.</span>cpr (from, to)](#apidoc.element.how-to-npm.cpr)
1.  [function <span class="apidocSignatureSpan">how-to-npm.</span>cwd ()](#apidoc.element.how-to-npm.cwd)
1.  [function <span class="apidocSignatureSpan">how-to-npm.</span>execute (args)](#apidoc.element.how-to-npm.execute)
1.  number <span class="apidocSignatureSpan">how-to-npm.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>_adventures
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>_events
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>_meta
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>appStorage
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>cli
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>current
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>domain
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>exerciseDir
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>exercises
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>i18n
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>i18n.lookup
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>i18n.mustache
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>i18n.mustache.Context.prototype
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>i18n.mustache.Scanner.prototype
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>i18n.mustache.Writer.prototype
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>languages
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>options
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>registry
1.  object <span class="apidocSignatureSpan">how-to-npm.</span>state
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>appDir
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>appName
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>appname
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>dataDir
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>datadir
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>defaultLang
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>lang
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>name
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>subtitle
1.  string <span class="apidocSignatureSpan">how-to-npm.</span>title

#### [module how-to-npm.appStorage](#apidoc.module.how-to-npm.appStorage)
1.  [function <span class="apidocSignatureSpan">how-to-npm.appStorage.</span>get (name)](#apidoc.element.how-to-npm.appStorage.get)
1.  [function <span class="apidocSignatureSpan">how-to-npm.appStorage.</span>reset ()](#apidoc.element.how-to-npm.appStorage.reset)
1.  [function <span class="apidocSignatureSpan">how-to-npm.appStorage.</span>save (name, data)](#apidoc.element.how-to-npm.appStorage.save)
1.  string <span class="apidocSignatureSpan">how-to-npm.appStorage.</span>dir

#### [module how-to-npm.i18n](#apidoc.module.how-to-npm.i18n)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>__ ()](#apidoc.element.how-to-npm.i18n.__)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>__n ()](#apidoc.element.how-to-npm.i18n.__n)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>change (lng)](#apidoc.element.how-to-npm.i18n.change)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>changeLang (lang)](#apidoc.element.how-to-npm.i18n.changeLang)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>changePrefix ()](#apidoc.element.how-to-npm.i18n.changePrefix)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>extend (obj)](#apidoc.element.how-to-npm.i18n.extend)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>fallback (key)](#apidoc.element.how-to-npm.i18n.fallback)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>has (key)](#apidoc.element.how-to-npm.i18n.has)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>lang ()](#apidoc.element.how-to-npm.i18n.lang)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>raw (key)](#apidoc.element.how-to-npm.i18n.raw)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>sub ()](#apidoc.element.how-to-npm.i18n.sub)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>translate ()](#apidoc.element.how-to-npm.i18n.translate)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>translateFirst ()](#apidoc.element.how-to-npm.i18n.translateFirst)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>vsprintf (fmt, argv)](#apidoc.element.how-to-npm.i18n.vsprintf)
1.  object <span class="apidocSignatureSpan">how-to-npm.i18n.</span>lookup
1.  object <span class="apidocSignatureSpan">how-to-npm.i18n.</span>mustache
1.  object <span class="apidocSignatureSpan">how-to-npm.i18n.</span>storage

#### [module how-to-npm.i18n.lookup](#apidoc.module.how-to-npm.i18n.lookup)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.lookup.</span>get (key)](#apidoc.element.how-to-npm.i18n.lookup.get)

#### [module how-to-npm.i18n.mustache](#apidoc.module.how-to-npm.i18n.mustache)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>Context (view, parentContext)](#apidoc.element.how-to-npm.i18n.mustache.Context)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>Scanner (string)](#apidoc.element.how-to-npm.i18n.mustache.Scanner)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>Writer ()](#apidoc.element.how-to-npm.i18n.mustache.Writer)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>clearCache ()](#apidoc.element.how-to-npm.i18n.mustache.clearCache)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>escape (string)](#apidoc.element.how-to-npm.i18n.mustache.escape)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>parse (template, tags)](#apidoc.element.how-to-npm.i18n.mustache.parse)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>render (template, view, partials)](#apidoc.element.how-to-npm.i18n.mustache.render)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>to_html (template, view, partials, send)](#apidoc.element.how-to-npm.i18n.mustache.to_html)
1.  object <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>tags
1.  string <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>name
1.  string <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>version

#### [module how-to-npm.i18n.mustache.Context.prototype](#apidoc.module.how-to-npm.i18n.mustache.Context.prototype)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Context.prototype.</span>lookup (name)](#apidoc.element.how-to-npm.i18n.mustache.Context.prototype.lookup)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Context.prototype.</span>push (view)](#apidoc.element.how-to-npm.i18n.mustache.Context.prototype.push)

#### [module how-to-npm.i18n.mustache.Scanner.prototype](#apidoc.module.how-to-npm.i18n.mustache.Scanner.prototype)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Scanner.prototype.</span>eos ()](#apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.eos)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Scanner.prototype.</span>scan (re)](#apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.scan)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Scanner.prototype.</span>scanUntil (re)](#apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.scanUntil)

#### [module how-to-npm.i18n.mustache.Writer.prototype](#apidoc.module.how-to-npm.i18n.mustache.Writer.prototype)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>clearCache ()](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.clearCache)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>parse (template, tags)](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.parse)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>render (template, view, partials)](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.render)
1.  [function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>renderTokens (tokens, context, partials, originalTemplate)](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.renderTokens)

#### [module how-to-npm.registry](#apidoc.module.how-to-npm.registry)
1.  [function <span class="apidocSignatureSpan">how-to-npm.registry.</span>daemon (args)](#apidoc.element.how-to-npm.registry.daemon)
1.  [function <span class="apidocSignatureSpan">how-to-npm.registry.</span>kill ()](#apidoc.element.how-to-npm.registry.kill)
1.  [function <span class="apidocSignatureSpan">how-to-npm.registry.</span>run (args)](#apidoc.element.how-to-npm.registry.run)



# <a name="apidoc.module.how-to-npm"></a>[module how-to-npm](#apidoc.module.how-to-npm)

#### <a name="apidoc.element.how-to-npm.__"></a>[function <span class="apidocSignatureSpan">how-to-npm.</span>__ ()](#apidoc.element.how-to-npm.__)
- description and source-code
```javascript
__ = function () { [native code] }
```
- example usage
```shell
...
  commands: [{
    name: 'reset-registry',
    handler: function (workshopper) {
      // Reset a bit harder, since we save other stuff in there.
      require('./lib/registry.js').kill()
      rimraf.sync(workshopper.dataDir)
      mkdirp.sync(workshopper.dataDir)
      console.log(workshopper.i18n.__('reset'))
    }
  }]
})

var fs = require('fs')
var path = require('path')
var rimraf = require('rimraf')
...
```

#### <a name="apidoc.element.how-to-npm.__n"></a>[function <span class="apidocSignatureSpan">how-to-npm.</span>__n ()](#apidoc.element.how-to-npm.__n)
- description and source-code
```javascript
__n = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.cpr"></a>[function <span class="apidocSignatureSpan">how-to-npm.</span>cpr (from, to)](#apidoc.element.how-to-npm.cpr)
- description and source-code
```javascript
function cpr(from, to) {
  var st = fs.statSync(from)
  if (st.isDirectory()) {
    mkdirp.sync(to)
    fs.readdirSync(from).forEach(function (file) {
      cpr(path.resolve(from, file), path.resolve(to, file))
    })
  } else {
    fs.writeFileSync(to, fs.readFileSync(from))
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.cwd"></a>[function <span class="apidocSignatureSpan">how-to-npm.</span>cwd ()](#apidoc.element.how-to-npm.cwd)
- description and source-code
```javascript
cwd = function () {
  var dataDir = shop.dataDir
  // verify we're in the right folder
  try {
    var cwd = fs.readFileSync(path.resolve(dataDir, 'cwd'), 'utf8').trim()
  } catch (er) {
    console.log(shop.i18n.__('error.not_setup'))
    return false
  }

  if (cwd === process.cwd()) return cwd

  console.log(shop.i18n.__('error.wrong_folder', {cwd: cwd}))
  return false
}
```
- example usage
```shell
...
  try {
    var cwd = fs.readFileSync(path.resolve(dataDir, 'cwd'), 'utf8').trim()
  } catch (er) {
    console.log(shop.i18n.__('error.not_setup'))
    return false
  }

  if (cwd === process.cwd()) return cwd

  console.log(shop.i18n.__('error.wrong_folder', {cwd: cwd}))
  return false
}

if (require.main === module) shop.execute(process.argv.slice(2))
...
```

#### <a name="apidoc.element.how-to-npm.execute"></a>[function <span class="apidocSignatureSpan">how-to-npm.</span>execute (args)](#apidoc.element.how-to-npm.execute)
- description and source-code
```javascript
execute = function (args) {
  return shop.constructor.prototype.execute.apply(this, arguments)
}
```
- example usage
```shell
...

  if (cwd === process.cwd()) return cwd

  console.log(shop.i18n.__('error.wrong_folder', {cwd: cwd}))
  return false
}

if (require.main === module) shop.execute(process.argv.slice(2))
...
```



# <a name="apidoc.module.how-to-npm.appStorage"></a>[module how-to-npm.appStorage](#apidoc.module.how-to-npm.appStorage)

#### <a name="apidoc.element.how-to-npm.appStorage.get"></a>[function <span class="apidocSignatureSpan">how-to-npm.appStorage.</span>get (name)](#apidoc.element.how-to-npm.appStorage.get)
- description and source-code
```javascript
function get(name) {
  var file = fileName(name)
  try {
    var fileData = fs.readFileSync(file, 'utf8')
  } catch (e) {
    // TODO: write this error in a log
    return null
  }
  try {
    return JSON.parse(fileData)
  } catch (e) {
    // TODO: write this error in a log
    return null
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.appStorage.reset"></a>[function <span class="apidocSignatureSpan">how-to-npm.appStorage.</span>reset ()](#apidoc.element.how-to-npm.appStorage.reset)
- description and source-code
```javascript
function reset() {
  rimraf.sync(dir)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.appStorage.save"></a>[function <span class="apidocSignatureSpan">how-to-npm.appStorage.</span>save (name, data)](#apidoc.element.how-to-npm.appStorage.save)
- description and source-code
```javascript
function save(name, data) {
  mkdirp.sync(dir)
  try {
    fs.writeFileSync(fileName(name), JSON.stringify(data, null, 2))
  } catch (e) {
    // TODO: write this error in a log
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.how-to-npm.i18n"></a>[module how-to-npm.i18n](#apidoc.module.how-to-npm.i18n)

#### <a name="apidoc.element.how-to-npm.i18n.__"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>__ ()](#apidoc.element.how-to-npm.i18n.__)
- description and source-code
```javascript
__ = function () { [native code] }
```
- example usage
```shell
...
  commands: [{
    name: 'reset-registry',
    handler: function (workshopper) {
      // Reset a bit harder, since we save other stuff in there.
      require('./lib/registry.js').kill()
      rimraf.sync(workshopper.dataDir)
      mkdirp.sync(workshopper.dataDir)
      console.log(workshopper.i18n.__('reset'))
    }
  }]
})

var fs = require('fs')
var path = require('path')
var rimraf = require('rimraf')
...
```

#### <a name="apidoc.element.how-to-npm.i18n.__n"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>__n ()](#apidoc.element.how-to-npm.i18n.__n)
- description and source-code
```javascript
__n = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.change"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>change (lng)](#apidoc.element.how-to-npm.i18n.change)
- description and source-code
```javascript
change = function (lng) {
  lang = choose(lng)
  translator.changeLang(lang)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.changeLang"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>changeLang (lang)](#apidoc.element.how-to-npm.i18n.changeLang)
- description and source-code
```javascript
function changeLang(lang) {
		result.changePrefix(lang + ".");
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.changePrefix"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>changePrefix ()](#apidoc.element.how-to-npm.i18n.changePrefix)
- description and source-code
```javascript
function changePrefix() {
			throw new Error("Forbidden by configuration");
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.extend"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>extend (obj)](#apidoc.element.how-to-npm.i18n.extend)
- description and source-code
```javascript
extend = function (obj) {
  return i18n(i18nExtend(result, {
    get: function (key) {
      return obj[key]
    }
  }))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.fallback"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>fallback (key)](#apidoc.element.how-to-npm.i18n.fallback)
- description and source-code
```javascript
function defaultFallback(key) {
	if (!key) {
		return "(?)";
	}
	return key;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.has"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>has (key)](#apidoc.element.how-to-npm.i18n.has)
- description and source-code
```javascript
function has(key) {
	var val = this.raw(key);
	return val !== undefined && val !== null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.lang"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>lang ()](#apidoc.element.how-to-npm.i18n.lang)
- description and source-code
```javascript
lang = function () {
  return lang
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.raw"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>raw (key)](#apidoc.element.how-to-npm.i18n.raw)
- description and source-code
```javascript
function raw(key) {
	return this.lookup.get(key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.sub"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>sub ()](#apidoc.element.how-to-npm.i18n.sub)
- description and source-code
```javascript
sub = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.translate"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>translate ()](#apidoc.element.how-to-npm.i18n.translate)
- description and source-code
```javascript
translate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.translateFirst"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>translateFirst ()](#apidoc.element.how-to-npm.i18n.translateFirst)
- description and source-code
```javascript
translateFirst = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.vsprintf"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.</span>vsprintf (fmt, argv)](#apidoc.element.how-to-npm.i18n.vsprintf)
- description and source-code
```javascript
vsprintf = function (fmt, argv) {
	var argvClone = argv.slice();
	argvClone.unshift(fmt);
	return sprintf.apply(null, argvClone);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.how-to-npm.i18n.lookup"></a>[module how-to-npm.i18n.lookup](#apidoc.module.how-to-npm.i18n.lookup)

#### <a name="apidoc.element.how-to-npm.i18n.lookup.get"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.lookup.</span>get (key)](#apidoc.element.how-to-npm.i18n.lookup.get)
- description and source-code
```javascript
get = function (key) {
  return i18n.has(key) ? i18n.__(key) : lookup.get(key);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.how-to-npm.i18n.mustache"></a>[module how-to-npm.i18n.mustache](#apidoc.module.how-to-npm.i18n.mustache)

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Context"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>Context (view, parentContext)](#apidoc.element.how-to-npm.i18n.mustache.Context)
- description and source-code
```javascript
function Context(view, parentContext) {
  this.view = view == null ? {} : view;
  this.cache = { '.': this.view };
  this.parent = parentContext;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Scanner"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>Scanner (string)](#apidoc.element.how-to-npm.i18n.mustache.Scanner)
- description and source-code
```javascript
function Scanner(string) {
  this.string = string;
  this.tail = string;
  this.pos = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Writer"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>Writer ()](#apidoc.element.how-to-npm.i18n.mustache.Writer)
- description and source-code
```javascript
function Writer() {
  this.cache = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.clearCache"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>clearCache ()](#apidoc.element.how-to-npm.i18n.mustache.clearCache)
- description and source-code
```javascript
clearCache = function () {
  return defaultWriter.clearCache();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.escape"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>escape (string)](#apidoc.element.how-to-npm.i18n.mustache.escape)
- description and source-code
```javascript
function escapeHtml(string) {
  return String(string).replace(/[&<>"'\/]/g, function (s) {
    return entityMap[s];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.parse"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>parse (template, tags)](#apidoc.element.how-to-npm.i18n.mustache.parse)
- description and source-code
```javascript
parse = function (template, tags) {
  return defaultWriter.parse(template, tags);
}
```
- example usage
```shell
...
  return res.end(JSON.stringify(data['dist-tags']))
}

if (req.method === 'POST' || req.method === 'PUT') {
  req.setEncoding('utf8')
  return req.pipe(concat(function (body) {
    console.error(body)
    body = JSON.parse(body)
    var dt
    if (tag) {
      if (semver.valid(body)) {
        data['dist-tags'][tag] = body
      } else {
        return _403(req, res, { error: 'invalid version' })
      }
...
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.render"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>render (template, view, partials)](#apidoc.element.how-to-npm.i18n.mustache.render)
- description and source-code
```javascript
render = function (template, view, partials) {
  return defaultWriter.render(template, view, partials);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.to_html"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.</span>to_html (template, view, partials, send)](#apidoc.element.how-to-npm.i18n.mustache.to_html)
- description and source-code
```javascript
to_html = function (template, view, partials, send) {
  var result = mustache.render(template, view, partials);

  if (isFunction(send)) {
    send(result);
  } else {
    return result;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.how-to-npm.i18n.mustache.Context.prototype"></a>[module how-to-npm.i18n.mustache.Context.prototype](#apidoc.module.how-to-npm.i18n.mustache.Context.prototype)

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Context.prototype.lookup"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Context.prototype.</span>lookup (name)](#apidoc.element.how-to-npm.i18n.mustache.Context.prototype.lookup)
- description and source-code
```javascript
lookup = function (name) {
  var value;
  if (name in this.cache) {
    value = this.cache[name];
  } else {
    var context = this;

    while (context) {
      if (name.indexOf('.') > 0) {
        value = context.view;

        var names = name.split('.'), i = 0;
        while (value != null && i < names.length) {
          value = value[names[i++]];
        }
      } else {
        value = context.view[name];
      }

      if (value != null) break;

      context = context.parent;
    }

    this.cache[name] = value;
  }

  if (isFunction(value)) {
    value = value.call(this.view);
  }

  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Context.prototype.push"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Context.prototype.</span>push (view)](#apidoc.element.how-to-npm.i18n.mustache.Context.prototype.push)
- description and source-code
```javascript
push = function (view) {
  return new Context(view, this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.how-to-npm.i18n.mustache.Scanner.prototype"></a>[module how-to-npm.i18n.mustache.Scanner.prototype](#apidoc.module.how-to-npm.i18n.mustache.Scanner.prototype)

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.eos"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Scanner.prototype.</span>eos ()](#apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.eos)
- description and source-code
```javascript
eos = function () {
  return this.tail === "";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.scan"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Scanner.prototype.</span>scan (re)](#apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.scan)
- description and source-code
```javascript
scan = function (re) {
  var match = this.tail.match(re);

  if (match && match.index === 0) {
    var string = match[0];
    this.tail = this.tail.substring(string.length);
    this.pos += string.length;
    return string;
  }

  return "";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.scanUntil"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Scanner.prototype.</span>scanUntil (re)](#apidoc.element.how-to-npm.i18n.mustache.Scanner.prototype.scanUntil)
- description and source-code
```javascript
scanUntil = function (re) {
  var index = this.tail.search(re), match;

  switch (index) {
  case -1:
    match = this.tail;
    this.tail = "";
    break;
  case 0:
    match = "";
    break;
  default:
    match = this.tail.substring(0, index);
    this.tail = this.tail.substring(index);
  }

  this.pos += match.length;

  return match;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.how-to-npm.i18n.mustache.Writer.prototype"></a>[module how-to-npm.i18n.mustache.Writer.prototype](#apidoc.module.how-to-npm.i18n.mustache.Writer.prototype)

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.clearCache"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>clearCache ()](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.clearCache)
- description and source-code
```javascript
clearCache = function () {
  this.cache = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.parse"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>parse (template, tags)](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.parse)
- description and source-code
```javascript
parse = function (template, tags) {
  var cache = this.cache;
  var tokens = cache[template];

  if (tokens == null) {
    tokens = cache[template] = parseTemplate(template, tags);
  }

  return tokens;
}
```
- example usage
```shell
...
  return res.end(JSON.stringify(data['dist-tags']))
}

if (req.method === 'POST' || req.method === 'PUT') {
  req.setEncoding('utf8')
  return req.pipe(concat(function (body) {
    console.error(body)
    body = JSON.parse(body)
    var dt
    if (tag) {
      if (semver.valid(body)) {
        data['dist-tags'][tag] = body
      } else {
        return _403(req, res, { error: 'invalid version' })
      }
...
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.render"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>render (template, view, partials)](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.render)
- description and source-code
```javascript
render = function (template, view, partials) {
  var tokens = this.parse(template);
  var context = (view instanceof Context) ? view : new Context(view);
  return this.renderTokens(tokens, context, partials, template);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.renderTokens"></a>[function <span class="apidocSignatureSpan">how-to-npm.i18n.mustache.Writer.prototype.</span>renderTokens (tokens, context, partials, originalTemplate)](#apidoc.element.how-to-npm.i18n.mustache.Writer.prototype.renderTokens)
- description and source-code
```javascript
renderTokens = function (tokens, context, partials, originalTemplate) {
  var buffer = '';

  // This function is used to render an arbitrary template
  // in the current context by higher-order sections.
  var self = this;
  function subRender(template) {
    return self.render(template, context, partials);
  }

  var token, value;
  for (var i = 0, len = tokens.length; i < len; ++i) {
    token = tokens[i];

    switch (token[0]) {
    case '#':
      value = context.lookup(token[1]);
      if (!value) continue;

      if (isArray(value)) {
        for (var j = 0, jlen = value.length; j < jlen; ++j) {
          buffer += this.renderTokens(token[4], context.push(value[j]), partials, originalTemplate);
        }
      } else if (typeof value === 'object' || typeof value === 'string') {
        buffer += this.renderTokens(token[4], context.push(value), partials, originalTemplate);
      } else if (isFunction(value)) {
        if (typeof originalTemplate !== 'string') {
          throw new Error('Cannot use higher-order sections without the original template');
        }

        // Extract the portion of the original template that the section contains.
        value = value.call(context.view, originalTemplate.slice(token[3], token[5]), subRender);

        if (value != null) buffer += value;
      } else {
        buffer += this.renderTokens(token[4], context, partials, originalTemplate);
      }

      break;
    case '^':
      value = context.lookup(token[1]);

      // Use JavaScript's definition of falsy. Include empty arrays.
      // See https://github.com/janl/mustache.js/issues/186
      if (!value || (isArray(value) && value.length === 0)) {
        buffer += this.renderTokens(token[4], context, partials, originalTemplate);
      }

      break;
    case '>':
      if (!partials) continue;
      value = isFunction(partials) ? partials(token[1]) : partials[token[1]];
      if (value != null) buffer += this.renderTokens(this.parse(value), context, partials, value);
      break;
    case '&':
      value = context.lookup(token[1]);
      if (value != null) buffer += value;
      break;
    case 'name':
      value = context.lookup(token[1]);
      if (value != null) buffer += mustache.escape(value);
      break;
    case 'text':
      buffer += token[1];
      break;
    }
  }

  return buffer;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.how-to-npm.registry"></a>[module how-to-npm.registry](#apidoc.module.how-to-npm.registry)

#### <a name="apidoc.element.how-to-npm.registry.daemon"></a>[function <span class="apidocSignatureSpan">how-to-npm.registry.</span>daemon (args)](#apidoc.element.how-to-npm.registry.daemon)
- description and source-code
```javascript
function daemon(args) {
  kill()

  var fd = fs.openSync(pidfile, 'wx')
  fs.writeSync(fd, process.pid + '\n')
  fs.closeSync(fd)

  var http = require('http')
  var lesson = args[0]
  var server = http.createServer(handler(args))
  server.listen(15443, function () {
    log('%s Listening', lesson)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.how-to-npm.registry.kill"></a>[function <span class="apidocSignatureSpan">how-to-npm.registry.</span>kill ()](#apidoc.element.how-to-npm.registry.kill)
- description and source-code
```javascript
function kill() {
  try {
    var pid = +fs.readFileSync(pidfile, 'ascii').trim()
    process.kill(pid, 'SIGKILL')
  } catch (er) {}
  try {
    fs.unlinkSync(pidfile)
  } catch (er) {}
}
```
- example usage
```shell
...
    bg: 'white',
    fg: 'red'
  },
  commands: [{
    name: 'reset-registry',
    handler: function (workshopper) {
      // Reset a bit harder, since we save other stuff in there.
      require('./lib/registry.js').kill()
      rimraf.sync(workshopper.dataDir)
      mkdirp.sync(workshopper.dataDir)
      console.log(workshopper.i18n.__('reset'))
    }
  }]
})
...
```

#### <a name="apidoc.element.how-to-npm.registry.run"></a>[function <span class="apidocSignatureSpan">how-to-npm.registry.</span>run (args)](#apidoc.element.how-to-npm.registry.run)
- description and source-code
```javascript
function run(args) {
  kill()

  var child = spawn(node, [__filename, 'daemon'].concat(args || []), {
    stdio: 'ignore',
    detached: true,
    cwd: path.resolve(__dirname, '..')
  })
  child.unref()
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
