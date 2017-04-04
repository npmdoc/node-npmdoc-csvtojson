# api documentation for  [csvtojson (v1.1.4)](http://keyangxiang.com/blog/csv2json/)  [![npm package](https://img.shields.io/npm/v/npmdoc-csvtojson.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-csvtojson) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-csvtojson.svg)](https://travis-ci.org/npmdoc/node-npmdoc-csvtojson)
#### A tool concentrating on converting csv data to JSON with customised parser supporting

[![NPM](https://nodei.co/npm/csvtojson.png?downloads=true)](https://www.npmjs.com/package/csvtojson)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csvtojson/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-csvtojson_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csvtojson/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-csvtojson/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-csvtojson/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Keyang Xiang",
        "email": "keyang.xiang@gmail.com"
    },
    "bin": {
        "csvtojson": "./bin/csvtojson"
    },
    "bugs": {
        "url": "https://github.com/Keyang/node-csvtojson/issues"
    },
    "contributors": [
        {
            "name": "Daniel Cohen",
            "email": "dcohenb@gmail.com",
            "url": "https://github.com/dcohenb"
        },
        {
            "name": "Trang",
            "email": "trangtungn@gmail.com",
            "url": "https://github.com/trangtungn"
        },
        {
            "name": "Matthias Lienau",
            "email": "matthias@mlienau.de",
            "url": "https://github.com/atufkas"
        },
        {
            "name": "Alec Fenichel",
            "email": "alec.fenichel@gmail.com",
            "url": "https://github.com/fenichelar"
        },
        {
            "name": "Blake Blackshear",
            "url": "https://github.com/blakeblackshear"
        },
        {
            "name": "Dimitri Kennedy",
            "email": "dimitrikennedy@gmail.com",
            "url": "https://github.com/roodboi"
        },
        {
            "url": "https://github.com/markwithers"
        },
        {
            "name": "Robert Porter",
            "url": "https://github.com/colarob"
        },
        {
            "name": "Jessica Good",
            "url": "https://github.com/jessicagood"
        },
        {
            "url": "https://github.com/jondayft"
        },
        {
            "name": "Dane Petersen",
            "url": "https://github.com/thegreatsunra"
        },
        {
            "name": "Jimi Ford",
            "url": "https://github.com/JimiHFord"
        },
        {
            "name": "Hocine Moukaideche",
            "url": "https://github.com/Off76"
        },
        {
            "name": "Keyang Xiang",
            "email": "keyang.xiang@gmail.com",
            "url": "https://github.com/Keyang"
        },
        {
            "name": "Ionică Bizău",
            "email": "contact@ionicabizau.net",
            "url": "https://github.com/IonicaBizau"
        },
        {
            "name": "Sean Lang",
            "email": "slang800@gmail.com",
            "url": "https://github.com/slang800"
        },
        {
            "name": "Tom Dodson",
            "email": "t3.dodson@gmail.com",
            "url": "https://github.com/t3dodson"
        },
        {
            "name": "Jeff Johnson",
            "url": "https://github.com/jeffcjohnson"
        },
        {
            "name": "Amila Welihinda",
            "email": "amilajack@gmail.com",
            "url": "https://github.com/amilajack"
        },
        {
            "name": "Zsolt R. Molnar",
            "url": "https://github.com/molnarzs"
        }
    ],
    "dependencies": {
        "lodash": "^4.17.3"
    },
    "description": "A tool concentrating on converting csv data to JSON with customised parser supporting",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-browserify": "^4.0.1",
        "grunt-contrib-jshint": "^0.11.2",
        "grunt-contrib-uglify": "^0.11.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-git": "^0.3.5",
        "grunt-madge": "0.0.6",
        "grunt-mocha-test": "^0.12.7",
        "grunt-newer": "^1.1.0",
        "imgur": "^0.1.5",
        "load-grunt-tasks": "^3.4.0",
        "minimist": "^1.2.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "8deafcd6e78dac01812a34ed022670e16d402fe7",
        "tarball": "https://registry.npmjs.org/csvtojson/-/csvtojson-1.1.4.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "590d5580348ede58e916277d8167f3f6e20f4219",
    "homepage": "http://keyangxiang.com/blog/csv2json/",
    "keywords": [
        "csv",
        "csv parser",
        "parse csv",
        "csvtojson",
        "json",
        "csv to json",
        "csv convert",
        "tojson",
        "convert csv to json",
        "csv-json"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "keyang",
            "email": "keyang.xiang@gmail.com"
        }
    ],
    "name": "csvtojson",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Keyang/node-csvtojson.git"
    },
    "scripts": {
        "test": "mocha ./test -R spec",
        "test-all": "mocha  ./test -R spec && CSV_WORKER=3 mocha ./test -R spec ",
        "test-debug": "mocha debug ./test -R spec"
    },
    "version": "1.1.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module csvtojson](#apidoc.module.csvtojson)
1.  [function <span class="apidocSignatureSpan">csvtojson.</span>Converter (params, options)](#apidoc.element.csvtojson.Converter)
1.  object <span class="apidocSignatureSpan">csvtojson.</span>Converter.prototype
1.  object <span class="apidocSignatureSpan">csvtojson.</span>interfaces

#### [module csvtojson.Converter](#apidoc.module.csvtojson.Converter)
1.  [function <span class="apidocSignatureSpan">csvtojson.</span>Converter (params, options)](#apidoc.element.csvtojson.Converter.Converter)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.</span>super_ (options)](#apidoc.element.csvtojson.Converter.super_)

#### [module csvtojson.Converter.prototype](#apidoc.module.csvtojson.Converter.prototype)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>_flush (cb)](#apidoc.element.csvtojson.Converter.prototype._flush)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>_preProcessLines (lines, startIdx)](#apidoc.element.csvtojson.Converter.prototype._preProcessLines)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>_transform (data, encoding, cb)](#apidoc.element.csvtojson.Converter.prototype._transform)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>checkAndFlush ()](#apidoc.element.csvtojson.Converter.prototype.checkAndFlush)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>emitResult (r)](#apidoc.element.csvtojson.Converter.prototype.emitResult)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>fromFile (filePath, cb)](#apidoc.element.csvtojson.Converter.prototype.fromFile)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>fromStream (readStream, cb)](#apidoc.element.csvtojson.Converter.prototype.fromStream)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>fromString (csvString, cb)](#apidoc.element.csvtojson.Converter.prototype.fromString)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>getEol (data)](#apidoc.element.csvtojson.Converter.prototype.getEol)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>initWorker ()](#apidoc.element.csvtojson.Converter.prototype.initWorker)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preFileLine (func)](#apidoc.element.csvtojson.Converter.prototype.preFileLine)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preProcessLine (line, lineNumber)](#apidoc.element.csvtojson.Converter.prototype.preProcessLine)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preProcessRaw (data, cb)](#apidoc.element.csvtojson.Converter.prototype.preProcessRaw)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preRawData (func)](#apidoc.element.csvtojson.Converter.prototype.preRawData)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>prepareData (data)](#apidoc.element.csvtojson.Converter.prototype.prepareData)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>processData (data, cb)](#apidoc.element.csvtojson.Converter.prototype.processData)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>processHead (fileLine, cb)](#apidoc.element.csvtojson.Converter.prototype.processHead)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>processResult (result)](#apidoc.element.csvtojson.Converter.prototype.processResult)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>setPartialData (d)](#apidoc.element.csvtojson.Converter.prototype.setPartialData)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>transf (func)](#apidoc.element.csvtojson.Converter.prototype.transf)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>workerProcess (fileLine, cb)](#apidoc.element.csvtojson.Converter.prototype.workerProcess)
1.  [function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>wrapCallback (cb, clean)](#apidoc.element.csvtojson.Converter.prototype.wrapCallback)



# <a name="apidoc.module.csvtojson"></a>[module csvtojson](#apidoc.module.csvtojson)

#### <a name="apidoc.element.csvtojson.Converter"></a>[function <span class="apidocSignatureSpan">csvtojson.</span>Converter (params, options)](#apidoc.element.csvtojson.Converter)
- description and source-code
```javascript
function Converter(params, options) {
  Transform.call(this, options);
  _param = defParam(params);
  this._options = options || {};
  this.param = _param;
  this.param._options = this._options;
  // this.resultObject = new Result(this);
  // this.pipe(this.resultObject); // it is important to have downstream for a transform otherwise it will stuck
  this.started = false;//indicate if parsing has started.
  this.recordNum = 0;
  this.lineNumber = 0; //file line number
  this._csvLineBuffer = "";
  this.lastIndex = 0; // index in result json array
  //this._pipe(this.lineParser).pipe(this.processor);
  // this.initNoFork();
  if (this.param.forked) {
    this.param.forked = false;
    this.workerNum = 2;
  }
  this.flushCb = null;
  this.processEnd = false;
  this.sequenceBuffer = [];
  this._needJson = null;
  this._needEmitResult = null;
  this._needEmitFinalResult = null;
  this._needEmitJson = null;
  this._needPush = null;
  this._needEmitCsv = null;
  this._csvTransf = null;
  this.finalResult = [];
  // this.on("data", function() {});
  this.on("error", emitDone(this));
  this.on("end", emitDone(this));
  this.initWorker();
  process.nextTick(function () {
    if (this._needEmitFinalResult === null) {
      this._needEmitFinalResult = this.listeners("end_parsed").length > 0
    }
    if (this._needEmitResult === null) {
      this._needEmitResult = this.listeners("record_parsed").length > 0
    }
    if (this._needEmitJson === null) {
      this._needEmitJson = this.listeners("json").length > 0
    }
    if (this._needEmitCsv === null) {
      this._needEmitCsv = this.listeners("csv").length > 0
    }
    if (this._needJson === null) {
      this._needJson = this._needEmitJson || this._needEmitFinalResult || this._needEmitResult || this.transform || this._options
.objectMode;
    }
    if (this._needPush === null) {
      this._needPush = this.listeners("data").length > 0 || this.listeners("readable").length > 0
      // this._needPush=false;
    }
    this.param._needParseJson = this._needJson || this._needPush;


  }.bind(this))
  return this;
}
```
- example usage
```shell
...
>csvtojson --help

# Params

The constructor of csv Converter allows parameters:

'''js
var converter=new require("csvtojson").Converter({
  constructResult:false,
  workerNum:4,
  noheader:true
});
'''

Following parameters are supported:
...
```



# <a name="apidoc.module.csvtojson.Converter"></a>[module csvtojson.Converter](#apidoc.module.csvtojson.Converter)

#### <a name="apidoc.element.csvtojson.Converter.Converter"></a>[function <span class="apidocSignatureSpan">csvtojson.</span>Converter (params, options)](#apidoc.element.csvtojson.Converter.Converter)
- description and source-code
```javascript
function Converter(params, options) {
  Transform.call(this, options);
  _param = defParam(params);
  this._options = options || {};
  this.param = _param;
  this.param._options = this._options;
  // this.resultObject = new Result(this);
  // this.pipe(this.resultObject); // it is important to have downstream for a transform otherwise it will stuck
  this.started = false;//indicate if parsing has started.
  this.recordNum = 0;
  this.lineNumber = 0; //file line number
  this._csvLineBuffer = "";
  this.lastIndex = 0; // index in result json array
  //this._pipe(this.lineParser).pipe(this.processor);
  // this.initNoFork();
  if (this.param.forked) {
    this.param.forked = false;
    this.workerNum = 2;
  }
  this.flushCb = null;
  this.processEnd = false;
  this.sequenceBuffer = [];
  this._needJson = null;
  this._needEmitResult = null;
  this._needEmitFinalResult = null;
  this._needEmitJson = null;
  this._needPush = null;
  this._needEmitCsv = null;
  this._csvTransf = null;
  this.finalResult = [];
  // this.on("data", function() {});
  this.on("error", emitDone(this));
  this.on("end", emitDone(this));
  this.initWorker();
  process.nextTick(function () {
    if (this._needEmitFinalResult === null) {
      this._needEmitFinalResult = this.listeners("end_parsed").length > 0
    }
    if (this._needEmitResult === null) {
      this._needEmitResult = this.listeners("record_parsed").length > 0
    }
    if (this._needEmitJson === null) {
      this._needEmitJson = this.listeners("json").length > 0
    }
    if (this._needEmitCsv === null) {
      this._needEmitCsv = this.listeners("csv").length > 0
    }
    if (this._needJson === null) {
      this._needJson = this._needEmitJson || this._needEmitFinalResult || this._needEmitResult || this.transform || this._options
.objectMode;
    }
    if (this._needPush === null) {
      this._needPush = this.listeners("data").length > 0 || this.listeners("readable").length > 0
      // this._needPush=false;
    }
    this.param._needParseJson = this._needJson || this._needPush;


  }.bind(this))
  return this;
}
```
- example usage
```shell
...
>csvtojson --help

# Params

The constructor of csv Converter allows parameters:

'''js
var converter=new require("csvtojson").Converter({
  constructResult:false,
  workerNum:4,
  noheader:true
});
'''

Following parameters are supported:
...
```

#### <a name="apidoc.element.csvtojson.Converter.super_"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.</span>super_ (options)](#apidoc.element.csvtojson.Converter.super_)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform))
    return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function')
      this._transform = options.transform;

    if (typeof options.flush === 'function')
      this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function() {
    if (typeof this._flush === 'function')
      this._flush(function(er) {
        done(stream, er);
      });
    else
      done(stream);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.csvtojson.Converter.prototype"></a>[module csvtojson.Converter.prototype](#apidoc.module.csvtojson.Converter.prototype)

#### <a name="apidoc.element.csvtojson.Converter.prototype._flush"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>_flush (cb)](#apidoc.element.csvtojson.Converter.prototype._flush)
- description and source-code
```javascript
_flush = function (cb) {
  var self = this;
  this.flushCb = function () {
    self.emit("end_parsed", self.finalResult);
    if (self.workerMgr) {
      self.workerMgr.destroyWorker();
    }
    cb()
    if (!self._needPush) {
      self.emit("end")
    }
  };
  if (this._csvLineBuffer.length > 0) {
    if (this._csvLineBuffer[this._csvLineBuffer.length - 1] != this.getEol()) {
      this._csvLineBuffer += this.getEol();
    }
    this.processData(this._csvLineBuffer, function () {
      this.checkAndFlush();
    }.bind(this));
  } else {
    this.checkAndFlush();
  }
  return;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype._preProcessLines"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>_preProcessLines (lines, startIdx)](#apidoc.element.csvtojson.Converter.prototype._preProcessLines)
- description and source-code
```javascript
_preProcessLines = function (lines, startIdx) {
  var rtn = []
  for (var i = 0; i < lines.length; i++) {
    var result = this.preProcessLine(lines[i], startIdx + i + 1)
    if (typeof result === "string") {
      rtn.push(result)
    } else {
      rtn.push(lines[i])
      this.emit("error", new Error("preProcessLine should return a string but got: " + JSON.stringify(result)))
    }
  }
  return rtn
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype._transform"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>_transform (data, encoding, cb)](#apidoc.element.csvtojson.Converter.prototype._transform)
- description and source-code
```javascript
_transform = function (data, encoding, cb) {
  if (this.param.toArrayString && this.started === false) {
    this.started = true;
    if (this._needPush) {
      this.push("[" + eol, "utf8");
    }
  }
  data = data.toString("utf8");
  var self = this;
  this.preProcessRaw(data, function (d) {
    if (d && d.length > 0) {
      self.processData(self.prepareData(d), cb);
    } else {
      cb();
    }
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.checkAndFlush"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>checkAndFlush ()](#apidoc.element.csvtojson.Converter.prototype.checkAndFlush)
- description and source-code
```javascript
checkAndFlush = function () {
  if (this._csvLineBuffer.length !== 0) {
    this.emit("error", CSVError.unclosed_quote(this.recordNum, this._csvLineBuffer), this._csvLineBuffer);
  }
  if (this.param.toArrayString && this._needPush) {
    this.push(eol + "]", "utf8");
  }
  if (this.workerMgr && this.workerMgr.isRunning()) {
    this.workerMgr.drain = function () {
      this.flushCb();
    }.bind(this);
  } else {
    this.flushCb();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.emitResult"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>emitResult (r)](#apidoc.element.csvtojson.Converter.prototype.emitResult)
- description and source-code
```javascript
emitResult = function (r) {
  var index = r.index;
  var row = r.row;
  var result = r.json;
  var resultJson = null;
  var resultStr = null;
  if (typeof result === "string") {
    resultStr = result;
  } else {
    resultJson = result;
  }
  if (resultJson === null && this._needJson) {
    resultJson = JSON.parse(resultStr)
    if (typeof row === "string") {
      row = JSON.parse(row)
    }
  }
  if (this.transform && typeof this.transform === "function") {
    this.transform(resultJson, row, index);
    resultStr = null;
  }
  if (this._needEmitJson) {
    this.emit("json", resultJson, index)
  }
  if (this._needEmitCsv) {
    if (typeof row === "string") {
      row = JSON.parse(row)
    }
    this.emit("csv", row, index)
  }
  if (this.param.constructResult && this._needEmitFinalResult) {
    this.finalResult.push(resultJson)
  }
  if (this._needEmitResult) {
    this.emit("record_parsed", resultJson, row, index);
  }
  if (this.param.toArrayString && index > 0 && this._needPush) {
    this.push("," + eol);
  }
  if (this._options && this._options.objectMode) {
    this.push(resultJson);
  } else {
    if (this._needPush) {
      if (resultStr === null) {
        resultStr = JSON.stringify(resultJson)
      }
      this.push(!this.param.toArrayString ? resultStr + eol : resultStr, "utf8");
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.fromFile"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>fromFile (filePath, cb)](#apidoc.element.csvtojson.Converter.prototype.fromFile)
- description and source-code
```javascript
fromFile = function (filePath, cb) {
  var fs = require('fs');
  var rs = null;
  this.wrapCallback(cb, function () {
    if (rs && rs.destroy) {
      rs.destroy();
    }
  });
  fs.exists(filePath, function (exist) {
    if (exist) {
      rs = fs.createReadStream(filePath);
      rs.pipe(this);
    } else {
      this.emit('error', new Error("File not exist"))
    }
  }.bind(this));
  return this;
}
```
- example usage
```shell
...

Or use fromFile convenient function

'''js
//Converter Class
var Converter = require("csvtojson").Converter;
var converter = new Converter({});
converter.fromFile("./file.csv",function(err,result){

});
'''

#### From Web

To convert any CSV data from readable stream just simply pipe in the data.
...
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.fromStream"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>fromStream (readStream, cb)](#apidoc.element.csvtojson.Converter.prototype.fromStream)
- description and source-code
```javascript
fromStream = function (readStream, cb) {
  if (cb && typeof cb === "function") {
    this.wrapCallback(cb);
  }
  readStream.pipe(this);
  return this;
}
```
- example usage
```shell
...
### From CSV Stream

'''js
//const csvReadStream -- Readable stream for csv source
const csv=require('csvtojson')

csv()
.fromStream(csvReadStream)
.on('csv',(csvRow)=>{
	// csvRow is an array
})
.on('done',(error)=>{

})
...
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.fromString"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>fromString (csvString, cb)](#apidoc.element.csvtojson.Converter.prototype.fromString)
- description and source-code
```javascript
fromString = function (csvString, cb) {
  if (typeof csvString != "string") {
    return cb(new Error("Passed CSV Data is not a string."));
  }
  if (cb && typeof cb === "function") {
    this.wrapCallback(cb, function () {
    });
  }
  process.nextTick(function () {
    this.end(csvString)
  }.bind(this))
  return this;
}
```
- example usage
```shell
...
'''

#### From String

'''js
var Converter = require("csvtojson").Converter;
var converter = new Converter({});
converter.fromString(csvString, function(err,result){
  //your code here
});
'''

### Command Line Tools

>csvtojson <csv file path>
...
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.getEol"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>getEol (data)](#apidoc.element.csvtojson.Converter.prototype.getEol)
- description and source-code
```javascript
getEol = function (data) {
  if (!this.param.eol && data) {
    for (var i = 0; i < data.length; i++) {
      if (data[i] === "\r") {
        if (data[i + 1] === "\n") {
          this.param.eol = "\r\n";
        } else {
          this.param.eol = "\r";
        }
        return this.param.eol;
      } else if (data[i] === "\n") {
        this.param.eol = "\n";
        return this.param.eol;
      }
    }
    this.param.eol = eol;
  }

  return this.param.eol || eol;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.initWorker"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>initWorker ()](#apidoc.element.csvtojson.Converter.prototype.initWorker)
- description and source-code
```javascript
initWorker = function () {
  var workerNum = this.param.workerNum - 1;
  if (workerNum > 0) {
    this.workerMgr = workerMgr();
    this.workerMgr.initWorker(workerNum, this.param);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.preFileLine"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preFileLine (func)](#apidoc.element.csvtojson.Converter.prototype.preFileLine)
- description and source-code
```javascript
preFileLine = function (func) {
  this.preProcessLine = func;
  return this;
}
```
- example usage
```shell
...
the function in 'preRawData' will be called directly with the string from upper stream.

### CSV File Line Hook

'''js
const csv=require('csvtojson')
csv()
.preFileLine((fileLineString, lineIdx)=>{
	if (lineIdx === 2){
		return fileLineString.replace('some value','another value')
	}
	return fileLineString
})
.on('json',(jsonObj)=>{
...
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.preProcessLine"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preProcessLine (line, lineNumber)](#apidoc.element.csvtojson.Converter.prototype.preProcessLine)
- description and source-code
```javascript
preProcessLine = function (line, lineNumber) {
  return line;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.preProcessRaw"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preProcessRaw (data, cb)](#apidoc.element.csvtojson.Converter.prototype.preProcessRaw)
- description and source-code
```javascript
preProcessRaw = function (data, cb) {
  cb(data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.preRawData"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>preRawData (func)](#apidoc.element.csvtojson.Converter.prototype.preRawData)
- description and source-code
```javascript
preRawData = function (func) {
  this.preProcessRaw = func;
  return this;
}
```
- example usage
```shell
...
## Hook & Transform

### Raw CSV Data Hook

'''js
const csv=require('csvtojson')
csv()
.preRawData((csvRawData,cb)=>{
	var newData=csvRawData.replace('some value','another value')
	cb(newData);
})
.on('json',(jsonObj)=>{

});
'''
...
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.prepareData"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>prepareData (data)](#apidoc.element.csvtojson.Converter.prototype.prepareData)
- description and source-code
```javascript
prepareData = function (data) {
  return this._csvLineBuffer + data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.processData"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>processData (data, cb)](#apidoc.element.csvtojson.Converter.prototype.processData)
- description and source-code
```javascript
processData = function (data, cb) {
  var params = this.param;
  if (params.ignoreEmpty && !params._headers) {
    data = data.trimLeft();
  }
  var fileLines = fileline(data, this.param)
  if (fileLines.lines.length > 0) {
    if (this.preProcessLine && typeof this.preProcessLine === "function") {
      fileLines.lines = this._preProcessLines(fileLines.lines, this.lastIndex)
    }
    if (!params._headers) { //header is not inited. init header
      this.processHead(fileLines, cb);
    } else {
      if (params.workerNum <= 1) {
        var lines = fileLineToCSVLine(fileLines, params);
        this.setPartialData(lines.partial);
        var jsonArr = linesToJson(lines.lines, params, this.recordNum);
        this.processResult(jsonArr)
        this.lastIndex += jsonArr.length;
        this.recordNum += jsonArr.length;
        cb();
      } else {
        this.workerProcess(fileLines, cb);
      }
    }
  } else {
    this.setPartialData(fileLines.partial)
    cb();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.processHead"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>processHead (fileLine, cb)](#apidoc.element.csvtojson.Converter.prototype.processHead)
- description and source-code
```javascript
processHead = function (fileLine, cb) {
  var params = this.param;
  if (!params._headers) { //header is not inited. init header
    var lines = fileLineToCSVLine(fileLine, params);
    this.setPartialData(lines.partial);
    if (params.noheader) {
      if (params.headers) {
        params._headers = params.headers;
      } else {
        params._headers = [];
      }
    } else {
      var headerRow = lines.lines.shift();
      if (params.headers) {
        params._headers = params.headers;
      } else {
        params._headers = headerRow;
      }
    }
    if (this.param.workerNum > 1) {
      this.workerMgr.setParams(params);
    }
    var res = linesToJson(lines.lines, params, 0);
    this.processResult(res);
    this.lastIndex += res.length;
    this.recordNum += res.length;
    cb();
  } else {
    cb();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.processResult"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>processResult (result)](#apidoc.element.csvtojson.Converter.prototype.processResult)
- description and source-code
```javascript
processResult = function (result) {

  for (var i = 0; i < result.length; i++) {
    var r = result[i];
    if (r.err) {
      this.emit("error", r.err);
    } else {
      this.emitResult(r);
    }
  }
  // this.lastIndex+=result.length;
  // cb();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.setPartialData"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>setPartialData (d)](#apidoc.element.csvtojson.Converter.prototype.setPartialData)
- description and source-code
```javascript
setPartialData = function (d) {
  this._csvLineBuffer = d;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.transf"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>transf (func)](#apidoc.element.csvtojson.Converter.prototype.transf)
- description and source-code
```javascript
transf = function (func) {
  this.transform = func;
  return this;
}
```
- example usage
```shell
...


### Result transform

'''js
const csv=require('csvtojson')
csv()
.transf((jsonObj,csvRow,index)=>{
	jsonObj.myNewKey='some value'
})
.on('json',(jsonObj)=>{
	console.log(jsonObj.myNewKey) // some value
});
'''
...
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.workerProcess"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>workerProcess (fileLine, cb)](#apidoc.element.csvtojson.Converter.prototype.workerProcess)
- description and source-code
```javascript
workerProcess = function (fileLine, cb) {
  var self = this;
  var line = fileLine
  var eol = this.getEol()
  this.setPartialData(line.partial)
  this.workerMgr.sendWorker(line.lines.join(eol) + eol, this.lastIndex, cb, function (results, lastIndex) {
    var cur = self.sequenceBuffer[0];
    if (cur.idx === lastIndex) {
      cur.result = results;
      var records = [];
      while (self.sequenceBuffer[0] && self.sequenceBuffer[0].result) {
        var buf = self.sequenceBuffer.shift();
        records = records.concat(buf.result)
      }
      self.processResult(records)
      self.recordNum += records.length;
    } else {
      for (var i = 0; i < self.sequenceBuffer.length; i++) {
        var buf = self.sequenceBuffer[i];
        if (buf.idx === lastIndex) {
          buf.result = results;
          break;
        }
      }
    }
    // self.processResult(JSON.parse(results),function(){},true);
  })
  this.sequenceBuffer.push({
    idx: this.lastIndex,
    result: null
  });
  this.lastIndex += line.lines.length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csvtojson.Converter.prototype.wrapCallback"></a>[function <span class="apidocSignatureSpan">csvtojson.Converter.prototype.</span>wrapCallback (cb, clean)](#apidoc.element.csvtojson.Converter.prototype.wrapCallback)
- description and source-code
```javascript
wrapCallback = function (cb, clean) {

  if (clean === undefined) {
    clean = function () { }
  }
  if (cb && typeof cb === "function") {
    this.once("end_parsed", function (res) {
      if (!this.hasError) {
        cb(null, res);
      }
    }.bind(this));
  }
  this.once("error", function (err) {
    this.hasError = true;
    if (cb && typeof cb === "function") {
      cb(err);
    }
    clean();
  }.bind(this));
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
