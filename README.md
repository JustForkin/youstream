YouStream
=========

[![Build Status](https://travis-ci.org/fand/youstream.svg?branch=master)](https://travis-ci.org/fand/youstream)
[![Code Climate](https://codeclimate.com/github/fand/youstream.png)](https://codeclimate.com/github/fand/youstream)
[![Coverage Status](https://coveralls.io/repos/fand/youstream/badge.png?branch=coveralls)](https://coveralls.io/r/fand/youstream?branch=coveralls)

[![NPM](https://nodei.co/npm/youstream.png?downloads=true&stars=true)](https://nodei.co/npm/youstream/)

A wrapper of [Youtube-dl](http://rg3.github.io/youtube-dl), returns the video as a stream.

## Installation

```bash
npm install youstream --save
```

## Usage

```js
  var youstream = require('youstream');
  var video = youstream(url);
  var output = fs.createWriteStream(path);
  video.pipe(output)
```

## Tests

npm test


## Release History

* 0.1.0 Initial release
