# path-format

> Node.js [`path.format(pathFormat)`](https://nodejs.org/api/path.html#path_path_format_pathobject) ponyfill.

> Ponyfill: A polyfill that doesn't overwrite the native method

## Install

```
$ npm install --save path-format
```

## Usage

```js
var pathFormat = require('path-format');

pathFormat({
    root : "/",
    dir : "/home/user/dir",
    base : "file.txt",
    ext : ".txt",
    name : "file"
})
//=> '/home/user/dir/file.txt'
```

## API

See [`path.format(pathObject)`](https://nodejs.org/api/path.html#path_path_format_pathobject) docs.

### pathFormat(path)

### pathFormat.posix(path)

The Posix specific version.

### pathFormat.win32(path)

The Windows specific version.
