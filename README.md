PYJSX
=====

Python Javascript Extensions allows you to leverage all the functionalities of
python in Javascript, acting as a form of virtual transpiler so youo can use
python methods like str.isalpha() or str.capitalize() or {}.iteritems from your
javascript applications.


# Installation

```shell

npm install pyjsx --save

```

# Usage

```node

//require your python types.
var {str, dict, list} = require('pyjsx');


var myName = str("raymond");
var modifedName = myName.capitalize();

```
