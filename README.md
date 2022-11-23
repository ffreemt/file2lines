# axios-elasticsearch [![npm version](https://badge.fury.io/js/file2lines.svg)](https://badge.fury.io/js/file2lines)
convert a file (autodetect encoding) to an array of lines/paras

## Installation
`npm i file2lines `

## Usage

```js
import file2lines from "file2lines";

const lines = file2line("./filename")  // remove blank lines

const lines = file2line("./filename", false)  // retain blank lines

// will throw exception if unable to detect file encoding
```
