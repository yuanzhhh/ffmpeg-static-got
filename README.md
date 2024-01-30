ffmpeg static binaries for Mac OSX and Linux and Windows

## Installation

This module is installed via npm:

``` bash
$ npm install ffmpeg-static-got
```

## Example Usage

Returns the path of a statically linked ffmpeg binary on the local filesystem.

``` js
var ffmpeg = require('ffmpeg-static-got');
console.log(ffmpeg.path);
```

Currently supports Mac OS X (64-bit), Linux (32 and 64-bit) and Windows
(32 and 64-bit).
