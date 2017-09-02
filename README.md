# CommentFarmer

## Intro

`CommentFarmer` is a node package that can parse out single or multi line comments from javascript or other languages which use the `//` or `/* */` system for denoting comments. Is it available on NPM for installation.

## Installation

To install type in your shell

```
$ npm install commentfarmer
```

## Usage

To initalize on instance of the parser,

```javascript

var ps = require('commentfarmer');
var parser = new ps.JSCommentParser();
```

to parse a string,

```javascript
parser.parse("var g = 7; //this line assigns a variable\n var h = 7 //so does this one\n");
```

to get the comments or clear them,

```javascript
console.log(parser.getComments()); // 'this line assigns a variable, so does this one'
parser.clearComments();
```

## License

This code is MIT licensed

## Contribution

Feel free to suggest changes or contribute