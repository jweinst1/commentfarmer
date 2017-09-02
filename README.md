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
