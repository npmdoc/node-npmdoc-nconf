# api documentation for  [nconf (v0.8.4)](https://github.com/flatiron/nconf#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nconf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nconf)
#### Hierarchical node.js configuration with files, environment variables, command-line arguments, and atomic object merging.

[![NPM](https://nodei.co/npm/nconf.png?downloads=true)](https://www.npmjs.com/package/nconf)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nconf/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-nconf_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nconf/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-nconf/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins",
        "email": "charlie.robbins@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/flatiron/nconf/issues"
    },
    "dependencies": {
        "async": "^1.4.0",
        "ini": "^1.3.0",
        "secure-keys": "^1.0.0",
        "yargs": "^3.19.0"
    },
    "description": "Hierarchical node.js configuration with files, environment variables, command-line arguments, and atomic object merging.",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "istanbul": "^0.4.1",
        "vows": "0.8.x"
    },
    "directories": {},
    "dist": {
        "shasum": "9502234f7ad6238cab7f92d7c068c20434d3ff93",
        "tarball": "https://registry.npmjs.org/nconf/-/nconf-0.8.4.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "3d4e58957878fab80fb3125784c04b615cf2f52e",
    "homepage": "https://github.com/flatiron/nconf#readme",
    "keywords": [
        "configuration",
        "key value store",
        "plugabble"
    ],
    "license": "MIT",
    "main": "./lib/nconf",
    "maintainers": [
        {
            "name": "indexzero",
            "email": "charlie.robbins@gmail.com"
        },
        {
            "name": "jcrugzz",
            "email": "jcrugzz@gmail.com"
        }
    ],
    "name": "nconf",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/flatiron/nconf.git"
    },
    "scripts": {
        "cover": "istanbul cover vows -- test/*-test.js test/**/*-test.js  --spec",
        "coveralls": "cat coverage/lcov.info | coveralls",
        "test": "vows test/*-test.js test/**/*-test.js --spec"
    },
    "version": "0.8.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module nconf](#apidoc.module.nconf)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Argv (options, usage)](#apidoc.element.nconf.Argv)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Env (options)](#apidoc.element.nconf.Env)
1.  [function <span class="apidocSignatureSpan">nconf.</span>File (options)](#apidoc.element.nconf.File)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Literal (options)](#apidoc.element.nconf.Literal)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Memory (options)](#apidoc.element.nconf.Memory)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Provider (options)](#apidoc.element.nconf.Provider)
1.  [function <span class="apidocSignatureSpan">nconf.</span>key ()](#apidoc.element.nconf.key)
1.  [function <span class="apidocSignatureSpan">nconf.</span>loadFiles (files, callback)](#apidoc.element.nconf.loadFiles)
1.  [function <span class="apidocSignatureSpan">nconf.</span>loadFilesSync (files)](#apidoc.element.nconf.loadFilesSync)
1.  [function <span class="apidocSignatureSpan">nconf.</span>path (key, separator)](#apidoc.element.nconf.path)
1.  object <span class="apidocSignatureSpan">nconf.</span>Argv.prototype
1.  object <span class="apidocSignatureSpan">nconf.</span>Env.prototype
1.  object <span class="apidocSignatureSpan">nconf.</span>File.prototype
1.  object <span class="apidocSignatureSpan">nconf.</span>Literal.prototype
1.  object <span class="apidocSignatureSpan">nconf.</span>Memory.prototype
1.  object <span class="apidocSignatureSpan">nconf.</span>Provider.prototype
1.  object <span class="apidocSignatureSpan">nconf.</span>formats
1.  object <span class="apidocSignatureSpan">nconf.</span>sources
1.  object <span class="apidocSignatureSpan">nconf.</span>stores
1.  string <span class="apidocSignatureSpan">nconf.</span>version

#### [module nconf.Argv](#apidoc.module.nconf.Argv)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Argv (options, usage)](#apidoc.element.nconf.Argv.Argv)
1.  [function <span class="apidocSignatureSpan">nconf.Argv.</span>super_ (options)](#apidoc.element.nconf.Argv.super_)

#### [module nconf.Argv.prototype](#apidoc.module.nconf.Argv.prototype)
1.  [function <span class="apidocSignatureSpan">nconf.Argv.prototype.</span>loadArgv ()](#apidoc.element.nconf.Argv.prototype.loadArgv)
1.  [function <span class="apidocSignatureSpan">nconf.Argv.prototype.</span>loadSync ()](#apidoc.element.nconf.Argv.prototype.loadSync)

#### [module nconf.Env](#apidoc.module.nconf.Env)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Env (options)](#apidoc.element.nconf.Env.Env)
1.  [function <span class="apidocSignatureSpan">nconf.Env.</span>super_ (options)](#apidoc.element.nconf.Env.super_)

#### [module nconf.Env.prototype](#apidoc.module.nconf.Env.prototype)
1.  [function <span class="apidocSignatureSpan">nconf.Env.prototype.</span>loadEnv ()](#apidoc.element.nconf.Env.prototype.loadEnv)
1.  [function <span class="apidocSignatureSpan">nconf.Env.prototype.</span>loadSync ()](#apidoc.element.nconf.Env.prototype.loadSync)

#### [module nconf.File](#apidoc.module.nconf.File)
1.  [function <span class="apidocSignatureSpan">nconf.</span>File (options)](#apidoc.element.nconf.File.File)
1.  [function <span class="apidocSignatureSpan">nconf.File.</span>super_ (options)](#apidoc.element.nconf.File.super_)

#### [module nconf.File.prototype](#apidoc.module.nconf.File.prototype)
1.  [function <span class="apidocSignatureSpan">nconf.File.prototype.</span>load (callback)](#apidoc.element.nconf.File.prototype.load)
1.  [function <span class="apidocSignatureSpan">nconf.File.prototype.</span>loadSync ()](#apidoc.element.nconf.File.prototype.loadSync)
1.  [function <span class="apidocSignatureSpan">nconf.File.prototype.</span>parse (contents)](#apidoc.element.nconf.File.prototype.parse)
1.  [function <span class="apidocSignatureSpan">nconf.File.prototype.</span>save (value, callback)](#apidoc.element.nconf.File.prototype.save)
1.  [function <span class="apidocSignatureSpan">nconf.File.prototype.</span>saveSync (value)](#apidoc.element.nconf.File.prototype.saveSync)
1.  [function <span class="apidocSignatureSpan">nconf.File.prototype.</span>search (base)](#apidoc.element.nconf.File.prototype.search)
1.  [function <span class="apidocSignatureSpan">nconf.File.prototype.</span>stringify ()](#apidoc.element.nconf.File.prototype.stringify)

#### [module nconf.Literal](#apidoc.module.nconf.Literal)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Literal (options)](#apidoc.element.nconf.Literal.Literal)
1.  [function <span class="apidocSignatureSpan">nconf.Literal.</span>super_ (options)](#apidoc.element.nconf.Literal.super_)

#### [module nconf.Literal.prototype](#apidoc.module.nconf.Literal.prototype)
1.  [function <span class="apidocSignatureSpan">nconf.Literal.prototype.</span>loadSync ()](#apidoc.element.nconf.Literal.prototype.loadSync)

#### [module nconf.Memory](#apidoc.module.nconf.Memory)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Memory (options)](#apidoc.element.nconf.Memory.Memory)

#### [module nconf.Memory.prototype](#apidoc.module.nconf.Memory.prototype)
1.  [function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>clear (key)](#apidoc.element.nconf.Memory.prototype.clear)
1.  [function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>get (key)](#apidoc.element.nconf.Memory.prototype.get)
1.  [function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>loadSync ()](#apidoc.element.nconf.Memory.prototype.loadSync)
1.  [function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>merge (key, value)](#apidoc.element.nconf.Memory.prototype.merge)
1.  [function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>reset ()](#apidoc.element.nconf.Memory.prototype.reset)
1.  [function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>set (key, value)](#apidoc.element.nconf.Memory.prototype.set)

#### [module nconf.Provider](#apidoc.module.nconf.Provider)
1.  [function <span class="apidocSignatureSpan">nconf.</span>Provider (options)](#apidoc.element.nconf.Provider.Provider)

#### [module nconf.Provider.prototype](#apidoc.module.nconf.Provider.prototype)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>_execute (action, syncLength)](#apidoc.element.nconf.Provider.prototype._execute)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>add (name, options, usage)](#apidoc.element.nconf.Provider.prototype.add)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>argv ()](#apidoc.element.nconf.Provider.prototype.argv)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>clear (key, callback)](#apidoc.element.nconf.Provider.prototype.clear)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>create (type, options, usage)](#apidoc.element.nconf.Provider.prototype.create)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>defaults (options)](#apidoc.element.nconf.Provider.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>env ()](#apidoc.element.nconf.Provider.prototype.env)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>file (key, options)](#apidoc.element.nconf.Provider.prototype.file)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>get (key, callback)](#apidoc.element.nconf.Provider.prototype.get)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>init (options)](#apidoc.element.nconf.Provider.prototype.init)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>load (callback)](#apidoc.element.nconf.Provider.prototype.load)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>merge ()](#apidoc.element.nconf.Provider.prototype.merge)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>overrides (options)](#apidoc.element.nconf.Provider.prototype.overrides)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>remove (name)](#apidoc.element.nconf.Provider.prototype.remove)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>required (keys)](#apidoc.element.nconf.Provider.prototype.required)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>reset (callback)](#apidoc.element.nconf.Provider.prototype.reset)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>save (value, callback)](#apidoc.element.nconf.Provider.prototype.save)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>set (key, value, callback)](#apidoc.element.nconf.Provider.prototype.set)
1.  [function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>use (name, options)](#apidoc.element.nconf.Provider.prototype.use)



# <a name="apidoc.module.nconf"></a>[module nconf](#apidoc.module.nconf)

#### <a name="apidoc.element.nconf.Argv"></a>[function <span class="apidocSignatureSpan">nconf.</span>Argv (options, usage)](#apidoc.element.nconf.Argv)
- description and source-code
```javascript
Argv = function (options, usage) {
  Memory.call(this, options);

  this.type     = 'argv';
  this.readOnly = true;
  this.options  = options || false;
  this.usage    = usage;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Env"></a>[function <span class="apidocSignatureSpan">nconf.</span>Env (options)](#apidoc.element.nconf.Env)
- description and source-code
```javascript
Env = function (options) {
  Memory.call(this, options);

  options        = options || {};
  this.type      = 'env';
  this.readOnly  = true;
  this.whitelist = options.whitelist || [];
  this.separator = options.separator || '';
  this.lowerCase = options.lowerCase || false;

  if (({}).toString.call(options.match) === '[object RegExp]'
      && typeof options !== 'string') {
    this.match = options.match;
  }

  if (options instanceof Array) {
    this.whitelist = options;
  }
  if (typeof(options) === 'string') {
    this.separator = options;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.File"></a>[function <span class="apidocSignatureSpan">nconf.</span>File (options)](#apidoc.element.nconf.File)
- description and source-code
```javascript
File = function (options) {
  if (!options || !options.file) {
    throw new Error ('Missing required option 'file'');
  }

  Memory.call(this, options);

  this.type    = 'file';
  this.file    = options.file;
  this.dir     = options.dir    || process.cwd();
  this.format  = options.format || formats.json;
  this.secure  = options.secure;
  this.spacing = options.json_spacing
    || options.spacing
    || 2;

  if (this.secure) {
    this.secure = Buffer.isBuffer(this.secure) || typeof this.secure === 'string'
      ? { secret: this.secure.toString() }
      : this.secure;

    this.secure.alg = this.secure.alg || 'aes-256-ctr';
    if (this.secure.secretPath) {
      this.secure.secret = fs.readFileSync(this.secure.secretPath, 'utf8');
    }

    if (!this.secure.secret) {
      throw new Error('secure.secret option is required');
    }

    this.keys = new Secure({
      secret: this.secure.secret,
      alg: this.secure.alg,
      format: this.format
    });
  }

  if (options.search) {
    this.search(this.dir);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Literal"></a>[function <span class="apidocSignatureSpan">nconf.</span>Literal (options)](#apidoc.element.nconf.Literal)
- description and source-code
```javascript
function Literal(options) {
  Memory.call(this, options);

  options       = options || {}
  this.type     = 'literal';
  this.readOnly = true;
  this.store    = options.store || options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Memory"></a>[function <span class="apidocSignatureSpan">nconf.</span>Memory (options)](#apidoc.element.nconf.Memory)
- description and source-code
```javascript
Memory = function (options) {
  options       = options || {};
  this.type     = 'memory';
  this.store    = {};
  this.mtimes   = {};
  this.readOnly = false;
  this.loadFrom = options.loadFrom || null;
  this.logicalSeparator = options.logicalSeparator || ':';

  if (this.loadFrom) {
    this.store = common.loadFilesSync(this.loadFrom);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Provider"></a>[function <span class="apidocSignatureSpan">nconf.</span>Provider (options)](#apidoc.element.nconf.Provider)
- description and source-code
```javascript
Provider = function (options) {
  //
  // Setup default options for working with 'stores',
  // 'overrides', 'process.env' and 'process.argv'.
  //
  options       = options || {};
  this.stores  = {};
  this.sources = [];
  this.init(options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.key"></a>[function <span class="apidocSignatureSpan">nconf.</span>key ()](#apidoc.element.nconf.key)
- description and source-code
```javascript
key = function () {
  return Array.prototype.slice.call(arguments).join(':');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.loadFiles"></a>[function <span class="apidocSignatureSpan">nconf.</span>loadFiles (files, callback)](#apidoc.element.nconf.loadFiles)
- description and source-code
```javascript
loadFiles = function (files, callback) {
  if (!files) {
    return callback(null, {});
  }

  var options = Array.isArray(files) ? { files: files } : files;

  //
  // Set the default JSON format if not already
  // specified
  //
  options.format = options.format || formats.json;

  function parseFile (file, next) {
    fs.readFile(file, function (err, data) {
      return !err
        ? next(null, options.format.parse(data.toString()))
        : next(err);
    });
  }

  async.map(options.files, parseFile, function (err, objs) {
    return err ? callback(err) : callback(null, common.merge(objs));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.loadFilesSync"></a>[function <span class="apidocSignatureSpan">nconf.</span>loadFilesSync (files)](#apidoc.element.nconf.loadFilesSync)
- description and source-code
```javascript
loadFilesSync = function (files) {
  if (!files) {
    return;
  }

  //
  // Set the default JSON format if not already
  // specified
  //
  var options = Array.isArray(files) ? { files: files } : files;
  options.format = options.format || formats.json;

  return common.merge(options.files.map(function (file) {
    return options.format.parse(fs.readFileSync(file, 'utf8'));
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.path"></a>[function <span class="apidocSignatureSpan">nconf.</span>path (key, separator)](#apidoc.element.nconf.path)
- description and source-code
```javascript
path = function (key, separator) {
  separator = separator || ':';
  return key == null ? [] : key.split(separator);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Argv"></a>[module nconf.Argv](#apidoc.module.nconf.Argv)

#### <a name="apidoc.element.nconf.Argv.Argv"></a>[function <span class="apidocSignatureSpan">nconf.</span>Argv (options, usage)](#apidoc.element.nconf.Argv.Argv)
- description and source-code
```javascript
Argv = function (options, usage) {
  Memory.call(this, options);

  this.type     = 'argv';
  this.readOnly = true;
  this.options  = options || false;
  this.usage    = usage;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Argv.super_"></a>[function <span class="apidocSignatureSpan">nconf.Argv.</span>super_ (options)](#apidoc.element.nconf.Argv.super_)
- description and source-code
```javascript
super_ = function (options) {
  options       = options || {};
  this.type     = 'memory';
  this.store    = {};
  this.mtimes   = {};
  this.readOnly = false;
  this.loadFrom = options.loadFrom || null;
  this.logicalSeparator = options.logicalSeparator || ':';

  if (this.loadFrom) {
    this.store = common.loadFilesSync(this.loadFrom);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Argv.prototype"></a>[module nconf.Argv.prototype](#apidoc.module.nconf.Argv.prototype)

#### <a name="apidoc.element.nconf.Argv.prototype.loadArgv"></a>[function <span class="apidocSignatureSpan">nconf.Argv.prototype.</span>loadArgv ()](#apidoc.element.nconf.Argv.prototype.loadArgv)
- description and source-code
```javascript
loadArgv = function () {
  var self = this,
      yargs, argv;

  yargs = typeof this.options === 'object'
    ? require('yargs')(process.argv.slice(2)).options(this.options)
    : require('yargs')(process.argv.slice(2));

  if (typeof this.usage === 'string') { yargs.usage(this.usage) }

  argv = yargs.argv

  if (!argv) {
    return;
  }

  this.readOnly = false;
  Object.keys(argv).forEach(function (key) {
    if (typeof argv[key] !== 'undefined') {
      self.set(key, argv[key]);
    }
  });

  this.showHelp = yargs.showHelp
  this.help     = yargs.help

  this.readOnly = true;
  return this.store;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Argv.prototype.loadSync"></a>[function <span class="apidocSignatureSpan">nconf.Argv.prototype.</span>loadSync ()](#apidoc.element.nconf.Argv.prototype.loadSync)
- description and source-code
```javascript
loadSync = function () {
  this.loadArgv();
  return this.store;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Env"></a>[module nconf.Env](#apidoc.module.nconf.Env)

#### <a name="apidoc.element.nconf.Env.Env"></a>[function <span class="apidocSignatureSpan">nconf.</span>Env (options)](#apidoc.element.nconf.Env.Env)
- description and source-code
```javascript
Env = function (options) {
  Memory.call(this, options);

  options        = options || {};
  this.type      = 'env';
  this.readOnly  = true;
  this.whitelist = options.whitelist || [];
  this.separator = options.separator || '';
  this.lowerCase = options.lowerCase || false;

  if (({}).toString.call(options.match) === '[object RegExp]'
      && typeof options !== 'string') {
    this.match = options.match;
  }

  if (options instanceof Array) {
    this.whitelist = options;
  }
  if (typeof(options) === 'string') {
    this.separator = options;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Env.super_"></a>[function <span class="apidocSignatureSpan">nconf.Env.</span>super_ (options)](#apidoc.element.nconf.Env.super_)
- description and source-code
```javascript
super_ = function (options) {
  options       = options || {};
  this.type     = 'memory';
  this.store    = {};
  this.mtimes   = {};
  this.readOnly = false;
  this.loadFrom = options.loadFrom || null;
  this.logicalSeparator = options.logicalSeparator || ':';

  if (this.loadFrom) {
    this.store = common.loadFilesSync(this.loadFrom);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Env.prototype"></a>[module nconf.Env.prototype](#apidoc.module.nconf.Env.prototype)

#### <a name="apidoc.element.nconf.Env.prototype.loadEnv"></a>[function <span class="apidocSignatureSpan">nconf.Env.prototype.</span>loadEnv ()](#apidoc.element.nconf.Env.prototype.loadEnv)
- description and source-code
```javascript
loadEnv = function () {
  var self = this;

  var env = process.env;

  if (this.lowerCase) {
    Object.keys(env).forEach(function (key) {
      env[key.toLowerCase()] = env[key];
    });
  }

  this.readOnly = false;
  Object.keys(env).filter(function (key) {
    if (self.match && self.whitelist.length) {
      return key.match(self.match) || self.whitelist.indexOf(key) !== -1
    }
    else if (self.match) {
      return key.match(self.match);
    }
    else {
      return !self.whitelist.length || self.whitelist.indexOf(key) !== -1
    }
  }).forEach(function (key) {
    if (self.separator) {
      self.set(common.key.apply(common, key.split(self.separator)), env[key]);
    }
    else {
      self.set(key, env[key]);
    }
  });

  this.readOnly = true;
  return this.store;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Env.prototype.loadSync"></a>[function <span class="apidocSignatureSpan">nconf.Env.prototype.</span>loadSync ()](#apidoc.element.nconf.Env.prototype.loadSync)
- description and source-code
```javascript
loadSync = function () {
  this.loadEnv();
  return this.store;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.File"></a>[module nconf.File](#apidoc.module.nconf.File)

#### <a name="apidoc.element.nconf.File.File"></a>[function <span class="apidocSignatureSpan">nconf.</span>File (options)](#apidoc.element.nconf.File.File)
- description and source-code
```javascript
File = function (options) {
  if (!options || !options.file) {
    throw new Error ('Missing required option 'file'');
  }

  Memory.call(this, options);

  this.type    = 'file';
  this.file    = options.file;
  this.dir     = options.dir    || process.cwd();
  this.format  = options.format || formats.json;
  this.secure  = options.secure;
  this.spacing = options.json_spacing
    || options.spacing
    || 2;

  if (this.secure) {
    this.secure = Buffer.isBuffer(this.secure) || typeof this.secure === 'string'
      ? { secret: this.secure.toString() }
      : this.secure;

    this.secure.alg = this.secure.alg || 'aes-256-ctr';
    if (this.secure.secretPath) {
      this.secure.secret = fs.readFileSync(this.secure.secretPath, 'utf8');
    }

    if (!this.secure.secret) {
      throw new Error('secure.secret option is required');
    }

    this.keys = new Secure({
      secret: this.secure.secret,
      alg: this.secure.alg,
      format: this.format
    });
  }

  if (options.search) {
    this.search(this.dir);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.File.super_"></a>[function <span class="apidocSignatureSpan">nconf.File.</span>super_ (options)](#apidoc.element.nconf.File.super_)
- description and source-code
```javascript
super_ = function (options) {
  options       = options || {};
  this.type     = 'memory';
  this.store    = {};
  this.mtimes   = {};
  this.readOnly = false;
  this.loadFrom = options.loadFrom || null;
  this.logicalSeparator = options.logicalSeparator || ':';

  if (this.loadFrom) {
    this.store = common.loadFilesSync(this.loadFrom);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.File.prototype"></a>[module nconf.File.prototype](#apidoc.module.nconf.File.prototype)

#### <a name="apidoc.element.nconf.File.prototype.load"></a>[function <span class="apidocSignatureSpan">nconf.File.prototype.</span>load (callback)](#apidoc.element.nconf.File.prototype.load)
- description and source-code
```javascript
load = function (callback) {
  var self = this;

  exists(self.file, function (exists) {
    if (!exists) {
      return callback(null, {});
    }

    //
    // Else, the path exists, read it from disk
    //
    fs.readFile(self.file, function (err, data) {
      if (err) {
        return callback(err);
      }

      try {
        // Deals with string that include BOM
        var stringData = data.toString();
        if (stringData.charAt(0) === '\uFEFF') {
          stringData = stringData.substr(1);
        }

        self.store = self.parse(stringData);
      }
      catch (ex) {
        return callback(new Error("Error parsing your configuration file: [" + self.file + ']: ' + ex.message));
      }

      callback(null, self.store);
    });
  });
}
```
- example usage
```shell
...
''' js
nconf.defaults({
  'some': 'default value'
});
'''

### File
Based on the Memory store, but provides additional methods '.save()' and '.load()' which allow you to read your configuration to
 and from file. As with the Memory store, all method calls are synchronous with the exception of '.save()' and '.load()' which take
 callback functions.

It is important to note that setting keys in the File engine will not be persisted to disk until a call to '.save()' is made. Note
 a custom key must be supplied as the first parameter for hierarchy to work if multiple files are used.

''' js
nconf.file('path/to/your/config.json');
// add multiple files, hierarchically. notice the unique key for each file
nconf.file('user', 'path/to/your/user.json');
...
```

#### <a name="apidoc.element.nconf.File.prototype.loadSync"></a>[function <span class="apidocSignatureSpan">nconf.File.prototype.</span>loadSync ()](#apidoc.element.nconf.File.prototype.loadSync)
- description and source-code
```javascript
loadSync = function () {
  if (!existsSync(this.file)) {
    this.store = {};
    return this.store;
  }

  //
  // Else, the path exists, read it from disk
  //
  try {
    // Deals with file that include BOM
    var fileData = fs.readFileSync(this.file, 'utf8');
    if (fileData.charAt(0) === '\uFEFF') {
      fileData = fileData.substr(1);
    }

    this.store = this.parse(fileData);
  }
  catch (ex) {
    throw new Error("Error parsing your configuration file: [" + this.file + ']: ' + ex.message);
  }

  return this.store;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.File.prototype.parse"></a>[function <span class="apidocSignatureSpan">nconf.File.prototype.</span>parse (contents)](#apidoc.element.nconf.File.prototype.parse)
- description and source-code
```javascript
parse = function (contents) {
  var parsed = this.format.parse(contents),
      self = this;

  if (!this.secure) {
    return parsed;
  }

  return this.keys.decrypt(parsed);

}
```
- example usage
```shell
...
  console.log('database: ' + nconf.get('database'));

  //
  // Save the configuration object to disk
  //
  nconf.save(function (err) {
    fs.readFile('path/to/your/config.json', function (err, data) {
      console.dir(JSON.parse(data.toString()))
    });
  });
'''

If you run the above script:

''' bash
...
```

#### <a name="apidoc.element.nconf.File.prototype.save"></a>[function <span class="apidocSignatureSpan">nconf.File.prototype.</span>save (value, callback)](#apidoc.element.nconf.File.prototype.save)
- description and source-code
```javascript
save = function (value, callback) {
  if (!callback) {
    callback = value;
    value = null;
  }

  fs.writeFile(this.file, this.stringify(), callback);
}
```
- example usage
```shell
...
  console.log('foo: ' + nconf.get('foo'));
  console.log('NODE_ENV: ' + nconf.get('NODE_ENV'));
  console.log('database: ' + nconf.get('database'));

  //
  // Save the configuration object to disk
  //
  nconf.save(function (err) {
    fs.readFile('path/to/your/config.json', function (err, data) {
      console.dir(JSON.parse(data.toString()))
    });
  });
'''

If you run the above script:
...
```

#### <a name="apidoc.element.nconf.File.prototype.saveSync"></a>[function <span class="apidocSignatureSpan">nconf.File.prototype.</span>saveSync (value)](#apidoc.element.nconf.File.prototype.saveSync)
- description and source-code
```javascript
saveSync = function (value) {
  fs.writeFileSync(this.file, this.stringify());
  return this.store;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.File.prototype.search"></a>[function <span class="apidocSignatureSpan">nconf.File.prototype.</span>search (base)](#apidoc.element.nconf.File.prototype.search)
- description and source-code
```javascript
search = function (base) {
  var looking = true,
      fullpath,
      previous,
      stats;

  base = base || process.cwd();

  if (this.file[0] === '/') {
    //
    // If filename for this instance is a fully qualified path
    // (i.e. it starts with a ''/'') then check if it exists
    //
    try {
      stats = fs.statSync(fs.realpathSync(this.file));
      if (stats.isFile()) {
        fullpath = this.file;
        looking = false;
      }
    }
    catch (ex) {
      //
      // Ignore errors
      //
    }
  }

  if (looking && base) {
    //
    // Attempt to stat the realpath located at 'base'
    // if the directory does not exist then return false.
    //
    try {
      var stat = fs.statSync(fs.realpathSync(base));
      looking = stat.isDirectory();
    }
    catch (ex) {
      return false;
    }
  }

  while (looking) {
    //
    // Iteratively look up the directory structure from 'base'
    //
    try {
      stats = fs.statSync(fs.realpathSync(fullpath = path.join(base, this.file)));
      looking = stats.isDirectory();
    }
    catch (ex) {
      previous = base;
      base = path.dirname(base);

      if (previous === base) {
        //
        // If we've reached the top of the directory structure then simply use
        // the default file path.
        //
        try {
          stats = fs.statSync(fs.realpathSync(fullpath = path.join(this.dir, this.file)));
          if (stats.isDirectory()) {
            fullpath = undefined;
          }
        }
        catch (ex) {
          //
          // Ignore errors
          //
        }

        looking = false;
      }
    }
  }

  //
  // Set the file for this instance to the fullpath
  // that we have found during the search. In the event that
  // the search was unsuccessful use the original value for 'this.file'.
  //
  this.file = fullpath || this.file;

  return fullpath;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.File.prototype.stringify"></a>[function <span class="apidocSignatureSpan">nconf.File.prototype.</span>stringify ()](#apidoc.element.nconf.File.prototype.stringify)
- description and source-code
```javascript
stringify = function () {
  var data = this.store,
      self = this;

  if (this.secure) {
    data = this.keys.encrypt(data);
  }

  return this.format.stringify(data, null, this.spacing);
}
```
- example usage
```shell
...
''' js
  nconf.file('path/to/your/config.json');
  // add multiple files, hierarchically. notice the unique key for each file
  nconf.file('user', 'path/to/your/user.json');
  nconf.file('global', 'path/to/your/global.json');
'''

The file store is also extensible for multiple file formats, defaulting to 'JSON'. To use a custom format, simply pass a format
object to the '.use()' method. This object must have '.parse()' and '.stringify()' methods just like the native 'JSON' object.

If the file does not exist at the provided path, the store will simply be empty.

#### Encrypting file contents

As of 'nconf@0.8.0' it is now possible to encrypt and decrypt file contents using the 'secure' option:
...
```



# <a name="apidoc.module.nconf.Literal"></a>[module nconf.Literal](#apidoc.module.nconf.Literal)

#### <a name="apidoc.element.nconf.Literal.Literal"></a>[function <span class="apidocSignatureSpan">nconf.</span>Literal (options)](#apidoc.element.nconf.Literal.Literal)
- description and source-code
```javascript
function Literal(options) {
  Memory.call(this, options);

  options       = options || {}
  this.type     = 'literal';
  this.readOnly = true;
  this.store    = options.store || options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Literal.super_"></a>[function <span class="apidocSignatureSpan">nconf.Literal.</span>super_ (options)](#apidoc.element.nconf.Literal.super_)
- description and source-code
```javascript
super_ = function (options) {
  options       = options || {};
  this.type     = 'memory';
  this.store    = {};
  this.mtimes   = {};
  this.readOnly = false;
  this.loadFrom = options.loadFrom || null;
  this.logicalSeparator = options.logicalSeparator || ':';

  if (this.loadFrom) {
    this.store = common.loadFilesSync(this.loadFrom);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Literal.prototype"></a>[module nconf.Literal.prototype](#apidoc.module.nconf.Literal.prototype)

#### <a name="apidoc.element.nconf.Literal.prototype.loadSync"></a>[function <span class="apidocSignatureSpan">nconf.Literal.prototype.</span>loadSync ()](#apidoc.element.nconf.Literal.prototype.loadSync)
- description and source-code
```javascript
loadSync = function () {
  return this.store;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Memory"></a>[module nconf.Memory](#apidoc.module.nconf.Memory)

#### <a name="apidoc.element.nconf.Memory.Memory"></a>[function <span class="apidocSignatureSpan">nconf.</span>Memory (options)](#apidoc.element.nconf.Memory.Memory)
- description and source-code
```javascript
Memory = function (options) {
  options       = options || {};
  this.type     = 'memory';
  this.store    = {};
  this.mtimes   = {};
  this.readOnly = false;
  this.loadFrom = options.loadFrom || null;
  this.logicalSeparator = options.logicalSeparator || ':';

  if (this.loadFrom) {
    this.store = common.loadFilesSync(this.loadFrom);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Memory.prototype"></a>[module nconf.Memory.prototype](#apidoc.module.nconf.Memory.prototype)

#### <a name="apidoc.element.nconf.Memory.prototype.clear"></a>[function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>clear (key)](#apidoc.element.nconf.Memory.prototype.clear)
- description and source-code
```javascript
clear = function (key) {
  if (this.readOnly) {
    return false;
  }

  var target = this.store,
      value  = target,
      path   = common.path(key, this.logicalSeparator);

  //
  // Remove the key from the set of 'mtimes' (modified times)
  //
  delete this.mtimes[key];

  //
  // Scope into the object to get the appropriate nested context
  //
  for (var i = 0; i < path.length - 1; i++) {
    key = path[i];
    value = target[key];
    if (typeof value !== 'function' && typeof value !== 'object') {
      return false;
    }
    target = value;
  }

  // Delete the key from the nested JSON structure
  key = path[i];
  delete target[key];
  return true;
}
```
- example usage
```shell
...
  nconf.required(['keya', 'keyb']);
  // Error: Missing required keys: keyb
'''

## Storage Engines

### Memory
A simple in-memory storage engine that stores a nested JSON representation of the configuration. To use this engine, just call '.
use()' with the appropriate arguments. All calls to '.get()', '.set()', '.clear()', '.reset()' methods are synchronous since we
are only dealing with an in-memory object.

''' js
  nconf.use('memory');
'''

### Argv
Responsible for loading the values parsed from 'process.argv' by 'yargs' into the configuration hierarchy. See the [yargs option
 docs](https://github.com/bcoe/yargs#optionskey-opt) for more on the option format.
...
```

#### <a name="apidoc.element.nconf.Memory.prototype.get"></a>[function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>get (key)](#apidoc.element.nconf.Memory.prototype.get)
- description and source-code
```javascript
get = function (key) {
  var target = this.store,
      path   = common.path(key, this.logicalSeparator);

  //
  // Scope into the object to get the appropriate nested context
  //
  while (path.length > 0) {
    key = path.shift();
    if (target && target.hasOwnProperty(key)) {
      target = target[key];
      continue;
    }
    return undefined;
  }

  return target;
}
```
- example usage
```shell
...
nconf.set('database:host', '127.0.0.1');
nconf.set('database:port', 5984);

//
// Get the entire database object from nconf. This will output
// { host: '127.0.0.1', port: 5984 }
//
console.log('foo: ' + nconf.get('foo'));
console.log('NODE_ENV: ' + nconf.get('NODE_ENV'));
console.log('database: ' + nconf.get('database'));

//
// Save the configuration object to disk
//
nconf.save(function (err) {
...
```

#### <a name="apidoc.element.nconf.Memory.prototype.loadSync"></a>[function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>loadSync ()](#apidoc.element.nconf.Memory.prototype.loadSync)
- description and source-code
```javascript
loadSync = function () {
  return this.store || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Memory.prototype.merge"></a>[function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>merge (key, value)](#apidoc.element.nconf.Memory.prototype.merge)
- description and source-code
```javascript
merge = function (key, value) {
  if (this.readOnly) {
    return false;
  }

  //
  // If the key is not an 'Object' or is an 'Array',
  // then simply set it. Merging is for Objects.
  //
  if (typeof value !== 'object' || Array.isArray(value) || value === null) {
    return this.set(key, value);
  }

  var self    = this,
      target  = this.store,
      path    = common.path(key, this.logicalSeparator),
      fullKey = key;

  //
  // Update the 'mtime' (modified time) of the key
  //
  this.mtimes[key] = Date.now();

  //
  // Scope into the object to get the appropriate nested context
  //
  while (path.length > 1) {
    key = path.shift();
    if (!target[key]) {
      target[key] = {};
    }

    target = target[key];
  }

  // Set the specified value in the nested JSON structure
  key = path.shift();

  //
  // If the current value at the key target is not an 'Object',
  // or is an 'Array' then simply override it because the new value
  // is an Object.
  //
  if (typeof target[key] !== 'object' || Array.isArray(target[key])) {
    target[key] = value;
    return true;
  }

  return Object.keys(value).every(function (nested) {
    return self.merge(common.keyed(self.logicalSeparator, fullKey, nested), value[nested]);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Memory.prototype.reset"></a>[function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>reset ()](#apidoc.element.nconf.Memory.prototype.reset)
- description and source-code
```javascript
reset = function () {
  if (this.readOnly) {
    return false;
  }

  this.mtimes = {};
  this.store  = {};
  return true;
}
```
- example usage
```shell
...
  nconf.required(['keya', 'keyb']);
  // Error: Missing required keys: keyb
'''

## Storage Engines

### Memory
A simple in-memory storage engine that stores a nested JSON representation of the configuration. To use this engine, just call '.
use()' with the appropriate arguments. All calls to '.get()', '.set()', '.clear()', '.reset()' methods are synchronous since we
are only dealing with an in-memory object.

''' js
  nconf.use('memory');
'''

### Argv
Responsible for loading the values parsed from 'process.argv' by 'yargs' into the configuration hierarchy. See the [yargs option
 docs](https://github.com/bcoe/yargs#optionskey-opt) for more on the option format.
...
```

#### <a name="apidoc.element.nconf.Memory.prototype.set"></a>[function <span class="apidocSignatureSpan">nconf.Memory.prototype.</span>set (key, value)](#apidoc.element.nconf.Memory.prototype.set)
- description and source-code
```javascript
set = function (key, value) {
  if (this.readOnly) {
    return false;
  }

  var target = this.store,
      path   = common.path(key, this.logicalSeparator);

  if (path.length === 0) {
    //
    // Root must be an object
    //
    if (!value || typeof value !== 'object') {
      return false;
    }
    else {
      this.reset();
      this.store = value;
      return true;
    }
  }

  //
  // Update the 'mtime' (modified time) of the key
  //
  this.mtimes[key] = Date.now();

  //
  // Scope into the object to get the appropriate nested context
  //
  while (path.length > 1) {
    key = path.shift();
    if (!target[key] || typeof target[key] !== 'object') {
      target[key] = {};
    }

    target = target[key];
  }

  // Set the specified value in the nested JSON structure
  key = path.shift();
  target[key] = value;
  return true;
}
```
- example usage
```shell
...
nconf.argv()
 .env()
 .file({ file: 'path/to/config.json' });

//
// Set a few variables on 'nconf'.
//
nconf.set('database:host', '127.0.0.1');
nconf.set('database:port', 5984);

//
// Get the entire database object from nconf. This will output
// { host: '127.0.0.1', port: 5984 }
//
console.log('foo: ' + nconf.get('foo'));
...
```



# <a name="apidoc.module.nconf.Provider"></a>[module nconf.Provider](#apidoc.module.nconf.Provider)

#### <a name="apidoc.element.nconf.Provider.Provider"></a>[function <span class="apidocSignatureSpan">nconf.</span>Provider (options)](#apidoc.element.nconf.Provider.Provider)
- description and source-code
```javascript
Provider = function (options) {
  //
  // Setup default options for working with 'stores',
  // 'overrides', 'process.env' and 'process.argv'.
  //
  options       = options || {};
  this.stores  = {};
  this.sources = [];
  this.init(options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nconf.Provider.prototype"></a>[module nconf.Provider.prototype](#apidoc.module.nconf.Provider.prototype)

#### <a name="apidoc.element.nconf.Provider.prototype._execute"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>_execute (action, syncLength)](#apidoc.element.nconf.Provider.prototype._execute)
- description and source-code
```javascript
_execute = function (action, syncLength) {
  var args = Array.prototype.slice.call(arguments, 2),
      callback = typeof args[args.length - 1] === 'function' && args.pop(),
      destructive = ['set', 'clear', 'merge', 'reset'].indexOf(action) !== -1,
      self = this,
      response,
      mergeObjs = [],
      keys = Object.keys(this.stores);


  function runAction (name, next) {
    var store = self.stores[name];

    if (destructive && store.readOnly) {
      return next();
    }

    return store[action].length > syncLength
      ? store[action].apply(store, args.concat(next))
      : next(null, store[action].apply(store, args));
  }

  if (callback) {
    return async.forEach(keys, runAction, function (err) {
      return err ? callback(err) : callback();
    });
  }

  keys.forEach(function (name) {
    if (typeof response === 'undefined') {
      var store = self.stores[name];

      if (destructive && store.readOnly) {
        return;
      }

      response = store[action].apply(store, args);

      // Merge objects if necessary
      if (response && action === 'get' && typeof response === 'object' && !Array.isArray(response)) {
        mergeObjs.push(response);
        response = undefined;
      }
    }
  });

  if (mergeObjs.length) {
    response = common.merge(mergeObjs.reverse());
  }

  return response;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Provider.prototype.add"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>add (name, options, usage)](#apidoc.element.nconf.Provider.prototype.add)
- description and source-code
```javascript
add = function (name, options, usage) {
  options  = options      || {};
  var type = options.type || name;

  if (!require('../nconf')[common.capitalize(type)]) {
    throw new Error('Cannot add store with unknown type: ' + type);
  }

  this.stores[name] = this.create(type, options, usage);

  if (this.stores[name].loadSync) {
    this.stores[name].loadSync();
  }

  return this;
}
```
- example usage
```shell
...
  });
'''

## API Documentation

The top-level of 'nconf' is an instance of the 'nconf.Provider' abstracts this all for you into a simple API.

### nconf.add(name, options)
Adds a new store with the specified 'name' and 'options'. If 'options.type' is not set, then 'name' will be used instead:

''' js
  nconf.add('supplied', { type: 'literal', store: { 'some': 'config' });
  nconf.add('user', { type: 'file', file: '/path/to/userconf.json' });
  nconf.add('global', { type: 'file', file: '/path/to/globalconf.json' });
'''
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.argv"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>argv ()](#apidoc.element.nconf.Provider.prototype.argv)
- description and source-code
```javascript
argv = function () {
  var args = [type].concat(Array.prototype.slice.call(arguments));
  return this.add.apply(this, args);
}
```
- example usage
```shell
...

//
// Setup nconf to use (in-order):
//   1. Command-line arguments
//   2. Environment variables
//   3. A file located at 'path/to/config.json'
//
nconf.argv()
 .env()
 .file({ file: 'path/to/config.json' });

//
// Set a few variables on 'nconf'.
//
nconf.set('database:host', '127.0.0.1');
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.clear"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>clear (key, callback)](#apidoc.element.nconf.Provider.prototype.clear)
- description and source-code
```javascript
clear = function (key, callback) {
  return this._execute('clear', 1, key, callback);
}
```
- example usage
```shell
...
  nconf.required(['keya', 'keyb']);
  // Error: Missing required keys: keyb
'''

## Storage Engines

### Memory
A simple in-memory storage engine that stores a nested JSON representation of the configuration. To use this engine, just call '.
use()' with the appropriate arguments. All calls to '.get()', '.set()', '.clear()', '.reset()' methods are synchronous since we
are only dealing with an in-memory object.

''' js
  nconf.use('memory');
'''

### Argv
Responsible for loading the values parsed from 'process.argv' by 'yargs' into the configuration hierarchy. See the [yargs option
 docs](https://github.com/bcoe/yargs#optionskey-opt) for more on the option format.
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.create"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>create (type, options, usage)](#apidoc.element.nconf.Provider.prototype.create)
- description and source-code
```javascript
create = function (type, options, usage) {
  return new (require('../nconf')[common.capitalize(type.toLowerCase())])(options, usage);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Provider.prototype.defaults"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>defaults (options)](#apidoc.element.nconf.Provider.prototype.defaults)
- description and source-code
```javascript
defaults = function (options) {
  options = options || {};
  if (!options.type) {
    options.type = 'literal';
  }

  return this.add(type, options);
}
```
- example usage
```shell
...
## Hierarchical configuration

Configuration management can get complicated very quickly for even trivial applications running in production. 'nconf' addresses
 this problem by enabling you to setup a hierarchy for different sources of configuration with no defaults. **The order in which
 you attach these configuration sources determines their priority in the hierarchy.** Let's take a look at the options available
 to you

1. **nconf.argv(options)** Loads 'process.argv' using yargs. If 'options' is supplied it is passed along to yargs.
2. **nconf.env(options)** Loads 'process.env' into the hierarchy.
3. **nconf.file(options)** Loads the configuration data at options.file into the hierarchy.
4. **nconf.defaults(options)** Loads the data in options.store into the hierarchy.
5. **nconf.overrides(options)** Loads the data in options.store into the hierarchy.

A sane default for this could be:

''' js
var nconf = require('nconf');
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.env"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>env ()](#apidoc.element.nconf.Provider.prototype.env)
- description and source-code
```javascript
env = function () {
  var args = [type].concat(Array.prototype.slice.call(arguments));
  return this.add.apply(this, args);
}
```
- example usage
```shell
...
//
// Setup nconf to use (in-order):
//   1. Command-line arguments
//   2. Environment variables
//   3. A file located at 'path/to/config.json'
//
nconf.argv()
 .env()
 .file({ file: 'path/to/config.json' });

//
// Set a few variables on 'nconf'.
//
nconf.set('database:host', '127.0.0.1');
nconf.set('database:port', 5984);
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.file"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>file (key, options)](#apidoc.element.nconf.Provider.prototype.file)
- description and source-code
```javascript
file = function (key, options) {
  if (arguments.length == 1) {
    options = typeof key === 'string' ? { file: key } : key;
    key = 'file';
  }
  else {
    options = typeof options === 'string'
      ? { file: options }
      : options;
  }

  options.type = 'file';
  return this.add(key, options);
}
```
- example usage
```shell
...
// Setup nconf to use (in-order):
//   1. Command-line arguments
//   2. Environment variables
//   3. A file located at 'path/to/config.json'
//
nconf.argv()
 .env()
 .file({ file: 'path/to/config.json' });

//
// Set a few variables on 'nconf'.
//
nconf.set('database:host', '127.0.0.1');
nconf.set('database:port', 5984);
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.get"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>get (key, callback)](#apidoc.element.nconf.Provider.prototype.get)
- description and source-code
```javascript
get = function (key, callback) {
  if (typeof key === 'function') {
    // Allow a * key call to be made
    callback = key;
    key = null;
  }

  //
  // If there is no callback we can short-circuit into the default
  // logic for traversing stores.
  //
  if (!callback) {
    return this._execute('get', 1, key, callback);
  }

  //
  // Otherwise the asynchronous, hierarchical 'get' is
  // slightly more complicated because we do not need to traverse
  // the entire set of stores, but up until there is a defined value.
  //
  var current = 0,
      names = Object.keys(this.stores),
      self = this,
      response,
      mergeObjs = [];

  async.whilst(function () {
    return typeof response === 'undefined' && current < names.length;
  }, function (next) {
    var store = self.stores[names[current]];
    current++;

    if (store.get.length >= 2) {
      return store.get(key, function (err, value) {
        if (err) {
          return next(err);
        }

        response = value;

        // Merge objects if necessary
        if (response && typeof response === 'object' && !Array.isArray(response)) {
          mergeObjs.push(response);
          response = undefined;
        }

        next();
      });
    }

    response = store.get(key);

    // Merge objects if necessary
    if (response && typeof response === 'object' && !Array.isArray(response)) {
      mergeObjs.push(response);
      response = undefined;
    }

    next();
  }, function (err) {
    if (!err && mergeObjs.length) {
      response = common.merge(mergeObjs.reverse());
    }
    return err ? callback(err) : callback(null, response);
  });
}
```
- example usage
```shell
...
nconf.set('database:host', '127.0.0.1');
nconf.set('database:port', 5984);

//
// Get the entire database object from nconf. This will output
// { host: '127.0.0.1', port: 5984 }
//
console.log('foo: ' + nconf.get('foo'));
console.log('NODE_ENV: ' + nconf.get('NODE_ENV'));
console.log('database: ' + nconf.get('database'));

//
// Save the configuration object to disk
//
nconf.save(function (err) {
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.init"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>init (options)](#apidoc.element.nconf.Provider.prototype.init)
- description and source-code
```javascript
init = function (options) {
  var self = this;

  //
  // Add any stores passed in through the options
  // to this instance.
  //
  if (options.type) {
    this.add(options.type, options);
  }
  else if (options.store) {
    this.add(options.store.name || options.store.type, options.store);
  }
  else if (options.stores) {
    Object.keys(options.stores).forEach(function (name) {
      var store = options.stores[name];
      self.add(store.name || name || store.type, store);
    });
  }

  //
  // Add any read-only sources to this instance
  //
  if (options.source) {
    this.sources.push(this.create(options.source.type || options.source.name, options.source));
  }
  else if (options.sources) {
    Object.keys(options.sources).forEach(function (name) {
      var source = options.sources[name];
      self.sources.push(self.create(source.type || source.name || name, source));
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Provider.prototype.load"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>load (callback)](#apidoc.element.nconf.Provider.prototype.load)
- description and source-code
```javascript
load = function (callback) {
  var self = this;

  function getStores () {
    var stores = Object.keys(self.stores);
    stores.reverse();
    return stores.map(function (name) {
      return self.stores[name];
    });
  }

  function loadStoreSync(store) {
    if (!store.loadSync) {
      throw new Error('nconf store ' + store.type + ' has no loadSync() method');
    }

    return store.loadSync();
  }

  function loadStore(store, next) {
    if (!store.load && !store.loadSync) {
      return next(new Error('nconf store ' + store.type + ' has no load() method'));
    }

    return store.loadSync
      ? next(null, store.loadSync())
      : store.load(next);
  }

  function loadBatch (targets, done) {
    if (!done) {
      return common.merge(targets.map(loadStoreSync));
    }

    async.map(targets, loadStore, function (err, objs) {
      return err ? done(err) : done(null, common.merge(objs));
    });
  }

  function mergeSources (data) {
    //
    // If 'data' was returned then merge it into
    // the system store.
    //
    if (data && typeof data === 'object') {
      self.use('sources', {
        type: 'literal',
        store: data
      });
    }
  }

  function loadSources () {
    var sourceHierarchy = self.sources.splice(0);
    sourceHierarchy.reverse();

    //
    // If we don't have a callback and the current
    // store is capable of loading synchronously
    // then do so.
    //
    if (!callback) {
      mergeSources(loadBatch(sourceHierarchy));
      return loadBatch(getStores());
    }

    loadBatch(sourceHierarchy, function (err, data) {
      if (err) {
        return callback(err);
      }

      mergeSources(data);
      return loadBatch(getStores(), callback);
    });
  }

  return self.sources.length
    ? loadSources()
    : loadBatch(getStores(), callback);
}
```
- example usage
```shell
...
''' js
nconf.defaults({
  'some': 'default value'
});
'''

### File
Based on the Memory store, but provides additional methods '.save()' and '.load()' which allow you to read your configuration to
 and from file. As with the Memory store, all method calls are synchronous with the exception of '.save()' and '.load()' which take
 callback functions.

It is important to note that setting keys in the File engine will not be persisted to disk until a call to '.save()' is made. Note
 a custom key must be supplied as the first parameter for hierarchy to work if multiple files are used.

''' js
nconf.file('path/to/your/config.json');
// add multiple files, hierarchically. notice the unique key for each file
nconf.file('user', 'path/to/your/user.json');
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.merge"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>merge ()](#apidoc.element.nconf.Provider.prototype.merge)
- description and source-code
```javascript
merge = function () {
  var self = this,
      args = Array.prototype.slice.call(arguments),
      callback = typeof args[args.length - 1] === 'function' && args.pop(),
      value = args.pop(),
      key = args.pop();

  function mergeProperty (prop, next) {
    return self._execute('merge', 2, prop, value[prop], next);
  }

  if (!key) {
    if (Array.isArray(value) || typeof value !== 'object') {
      return onError(new Error('Cannot merge non-Object into top-level.'), callback);
    }

    return async.forEach(Object.keys(value), mergeProperty, callback || function () { })
  }

  return this._execute('merge', 2, key, value, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nconf.Provider.prototype.overrides"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>overrides (options)](#apidoc.element.nconf.Provider.prototype.overrides)
- description and source-code
```javascript
overrides = function (options) {
  options = options || {};
  if (!options.type) {
    options.type = 'literal';
  }

  return this.add(type, options);
}
```
- example usage
```shell
...

Configuration management can get complicated very quickly for even trivial applications running in production. 'nconf' addresses
 this problem by enabling you to setup a hierarchy for different sources of configuration with no defaults. **The order in which
 you attach these configuration sources determines their priority in the hierarchy.** Let's take a look at the options available
 to you

1. **nconf.argv(options)** Loads 'process.argv' using yargs. If 'options' is supplied it is passed along to yargs.
2. **nconf.env(options)** Loads 'process.env' into the hierarchy.
3. **nconf.file(options)** Loads the configuration data at options.file into the hierarchy.
4. **nconf.defaults(options)** Loads the data in options.store into the hierarchy.
5. **nconf.overrides(options)** Loads the data in options.store into the hierarchy.

A sane default for this could be:

''' js
var nconf = require('nconf');

//
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.remove"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>remove (name)](#apidoc.element.nconf.Provider.prototype.remove)
- description and source-code
```javascript
remove = function (name) {
  delete this.stores[name];
  return this;
}
```
- example usage
```shell
...

  //
  // Replace the file store with new settings
  //
  nconf.use('file', { file: 'path/to/a-new/config-file.json' });
'''

### nconf.remove(name)
Removes the store with the specified 'name.' The configuration stored at that level will no longer be used for lookup(s).

''' js
  nconf.remove('file');
'''y

### nconf.required(keys)
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.required"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>required (keys)](#apidoc.element.nconf.Provider.prototype.required)
- description and source-code
```javascript
required = function (keys) {
  if (!Array.isArray(keys)) {
    throw new Error('Incorrect parameter, array expected');
  }

  var missing = [];
  keys.forEach(function(key) {
    if (typeof this.get(key) === 'undefined') {
      missing.push(key);
    }
  }, this);

  if (missing.length) {
    throw new Error('Missing required keys: ' + missing.join(', '));
  } else {
    return true;
  }

}
```
- example usage
```shell
...
### nconf.remove(name)
Removes the store with the specified 'name.' The configuration stored at that level will no longer be used for lookup(s).

''' js
nconf.remove('file');
'''y

### nconf.required(keys)
Declares a set of string keys to be mandatory, and throw an error if any are missing.

'''js
nconf.defaults({
  keya: 'a',
});
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.reset"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>reset (callback)](#apidoc.element.nconf.Provider.prototype.reset)
- description and source-code
```javascript
reset = function (callback) {
  return this._execute('reset', 0, callback);
}
```
- example usage
```shell
...
  nconf.required(['keya', 'keyb']);
  // Error: Missing required keys: keyb
'''

## Storage Engines

### Memory
A simple in-memory storage engine that stores a nested JSON representation of the configuration. To use this engine, just call '.
use()' with the appropriate arguments. All calls to '.get()', '.set()', '.clear()', '.reset()' methods are synchronous since we
are only dealing with an in-memory object.

''' js
  nconf.use('memory');
'''

### Argv
Responsible for loading the values parsed from 'process.argv' by 'yargs' into the configuration hierarchy. See the [yargs option
 docs](https://github.com/bcoe/yargs#optionskey-opt) for more on the option format.
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.save"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>save (value, callback)](#apidoc.element.nconf.Provider.prototype.save)
- description and source-code
```javascript
save = function (value, callback) {
  if (!callback && typeof value === 'function') {
    callback = value;
    value = null;
  }

  var self = this,
      names = Object.keys(this.stores);

  function saveStoreSync(memo, name) {
    var store = self.stores[name];

    //
    // If the 'store' doesn't have a 'saveSync' method,
    // just ignore it and continue.
    //
    if (store.saveSync) {
      var ret = store.saveSync();
      if (typeof ret == 'object' && ret !== null) {
        memo.push(ret);
      }
    }
    return memo;
  }

  function saveStore(memo, name, next) {
    var store = self.stores[name];

    //
    // If the 'store' doesn't have a 'save' or saveSync'
    // method(s), just ignore it and continue.
    //

    if (store.save) {
      return store.save(value, function (err, data) {
        if (err) {
          return next(err);
        }

        if (typeof data == 'object' && data !== null) {
          memo.push(data);
        }

        next(null, memo);
      });
    }
    else if (store.saveSync) {
      memo.push(store.saveSync());
    }

    next(null, memo);
  }

  //
  // If we don't have a callback and the current
  // store is capable of saving synchronously
  // then do so.
  //
  if (!callback) {
    return common.merge(names.reduce(saveStoreSync, []));
  }

  async.reduce(names, [], saveStore, function (err, objs) {
    return err ? callback(err) : callback(null, common.merge(objs));
  });
}
```
- example usage
```shell
...
  console.log('foo: ' + nconf.get('foo'));
  console.log('NODE_ENV: ' + nconf.get('NODE_ENV'));
  console.log('database: ' + nconf.get('database'));

  //
  // Save the configuration object to disk
  //
  nconf.save(function (err) {
    fs.readFile('path/to/your/config.json', function (err, data) {
      console.dir(JSON.parse(data.toString()))
    });
  });
'''

If you run the above script:
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.set"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>set (key, value, callback)](#apidoc.element.nconf.Provider.prototype.set)
- description and source-code
```javascript
set = function (key, value, callback) {
  return this._execute('set', 2, key, value, callback);
}
```
- example usage
```shell
...
nconf.argv()
 .env()
 .file({ file: 'path/to/config.json' });

//
// Set a few variables on 'nconf'.
//
nconf.set('database:host', '127.0.0.1');
nconf.set('database:port', 5984);

//
// Get the entire database object from nconf. This will output
// { host: '127.0.0.1', port: 5984 }
//
console.log('foo: ' + nconf.get('foo'));
...
```

#### <a name="apidoc.element.nconf.Provider.prototype.use"></a>[function <span class="apidocSignatureSpan">nconf.Provider.prototype.</span>use (name, options)](#apidoc.element.nconf.Provider.prototype.use)
- description and source-code
```javascript
use = function (name, options) {
  options  = options      || {};
  var type = options.type || name;

  function sameOptions (store) {
    return Object.keys(options).every(function (key) {
      return options[key] === store[key];
    });
  }

  var store = this.stores[name],
      update = store && !sameOptions(store);

  if (!store || update) {
    if (update) {
      this.remove(name);
    }

    this.add(name, options);
  }

  return this;
}
```
- example usage
```shell
...

''' js
nconf.add('supplied', { type: 'literal', store: { 'some': 'config' });
nconf.add('user', { type: 'file', file: '/path/to/userconf.json' });
nconf.add('global', { type: 'file', file: '/path/to/globalconf.json' });
'''

### nconf.use(name, options)
Similar to 'nconf.add', except that it can replace an existing store if new options are provided

''' js
//
// Load a file store onto nconf with the specified settings
//
nconf.use('file', { file: '/path/to/some/config-file.json' });
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
